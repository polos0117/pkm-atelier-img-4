# 터검니 (0610 · Axew) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 8594c24 · 2026-11-01T14:51:25.941Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 610 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 390 | `1e035da98bec` | `터검니_light_glossy_promo_f.webp` |
| ② | heavy | ① 터검니_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `a50bfb6ab5d6` | `터검니_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 터검니_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `e5c07f42655c` | `터검니_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 터검니_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `a62cef16ca93` | `터검니_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 터검니_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `1cbeaf5fe9d0` | `터검니_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 터검니_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `1c2e3eb9184e` | `터검니_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 터검니_light_glossy_promo_f.webp | `casual1-prompt.txt` | 633 | `327156732ddf` | `터검니_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 터검니_light_glossy_promo_f.webp | `casual2-prompt.txt` | 651 | `5abf7cf666d4` | `터검니_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 터검니_light_glossy_promo_f.webp | `casual3-prompt.txt` | 809 | `6e1b2280c96d` | `터검니_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 런웨이 | a fashion runway under white spotlights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 dress · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 3/4 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 드러내기 mini length, high thigh slit · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 직업복 · 연구복 | a white lab coat over a fitted knit top and slim trousers |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 coat + knit_top + trousers · 드러내기 cropped hem, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit
