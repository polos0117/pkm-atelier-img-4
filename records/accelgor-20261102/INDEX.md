# 어지리더 (0617 · Accelgor) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 454fcdb · 2026-11-01T21:34:01.631Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 617 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 461 | `01b41ba17e44` | `어지리더_light_glossy_promo_f.webp` |
| ② | heavy | ① 어지리더_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `02615bd0e186` | `어지리더_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 어지리더_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `940a4987cb90` | `어지리더_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 어지리더_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `84f6eb6a7c66` | `어지리더_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 어지리더_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `bb421c13798c` | `어지리더_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 어지리더_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `f04206fddff3` | `어지리더_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 어지리더_light_glossy_promo_f.webp | `casual1-prompt.txt` | 760 | `60a61cabc3c8` | `어지리더_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 어지리더_light_glossy_promo_f.webp | `casual2-prompt.txt` | 765 | `f8a81aa99f5b` | `어지리더_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 어지리더_light_glossy_promo_f.webp | `casual3-prompt.txt` | 669 | `54fad3ccf570` | `어지리더_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | lap · natural |  |

옷 종류 apron · 드러내기 cropped hem, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 동반 호텔 | the reception counter of a Pokémon-friendly hotel |
| 역할 | — |  |
| 의상 | 홈웨어 · 아침 로브 | a loosely tied robe |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 robe · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공연장 대기실 | a backstage dressing room with a bulb-lit mirror, a vanity table and costume racks |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 옆모습 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | prop · prop · 꽃다발 · 두 손으로 꽃다발을 든다 | holds a small bouquet in both hands at her waist |

옷 종류 crop_top + skirt · 드러내기 halter neck, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
