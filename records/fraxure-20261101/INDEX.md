# 액슨도 (0611 · Fraxure) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 8594c24 · 2026-11-01T14:51:26.069Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 611 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 388 | `bb741a0e34a2` | `액슨도_light_glossy_promo_f.webp` |
| ② | heavy | ① 액슨도_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `7fce510cf316` | `액슨도_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 액슨도_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `14fc23a092f7` | `액슨도_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 액슨도_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `01c8a874e29e` | `액슨도_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 액슨도_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `f7a0045c981e` | `액슨도_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 액슨도_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `aa90f3bb4c83` | `액슨도_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 액슨도_light_glossy_promo_f.webp | `casual1-prompt.txt` | 875 | `f7ad48e4f05d` | `액슨도_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 액슨도_light_glossy_promo_f.webp | `casual2-prompt.txt` | 717 | `f036c8129cd6` | `액슨도_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 액슨도_light_glossy_promo_f.webp | `casual3-prompt.txt` | 722 | `11aa940ac2af` | `액슨도_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 거실 | her living room with a deep sofa, floor cushions and a low table |
| 역할 | — |  |
| 의상 | 직업복 · 연구복 | a white lab coat over a fitted knit top and slim trousers |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 기타 · 기타를 든다 | carries an acoustic guitar by its neck at her side |

옷 종류 coat + knit_top + trousers · 드러내기 open back, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 잔·컵 · 잔을 입에 댄다 | brings a cup to her lips |

옷 종류 lingerie_set + skirt · 드러내기 plunging neckline, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 밤 택시 | the back seat of a taxi at night, city lights streaking past |
| 역할 | — |  |
| 의상 | 란제리풍 · 코르셋풍 | a corset-inspired bodice with visible boning seams and a matching high-waisted piece |
| 몸 자세 · 구도 | 의자에 앉기 · waist_up · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 드러내기 bare midriff, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit
