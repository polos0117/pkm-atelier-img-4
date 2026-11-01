# 너트령 (0598 · Ferrothorn) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 ce4861f · 2026-11-01T05:34:59.987Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 598 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 404 | `a4a09506801a` | `너트령_light_glossy_promo_f.webp` |
| ② | heavy | ① 너트령_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `5b756e61558c` | `너트령_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 너트령_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `a3fd6df1e768` | `너트령_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 너트령_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 251 | `77a13c169b97` | `너트령_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 너트령_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 257 | `568f831ea7c6` | `너트령_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 너트령_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 250 | `7730af487a46` | `너트령_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 너트령_light_glossy_promo_f.webp | `casual1-prompt.txt` | 742 | `a49716933971` | `너트령_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 너트령_light_glossy_promo_f.webp | `casual2-prompt.txt` | 708 | `0dd56534618b` | `너트령_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 너트령_light_glossy_promo_f.webp | `casual3-prompt.txt` | 683 | `7aa47a7e57c5` | `너트령_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + skirt · 드러내기 bare midriff, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 뒤 3/4 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 드러내기 strapless top, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 요정 숲 정원 | a misty enchanted garden of moss, ivy and lanterns |
| 역할 | — |  |
| 의상 | 레트로 · 80년대 에어로빅 | an 1980s high-cut aerobics leotard over shiny tights with leg warmers and a headband |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 leggings · 드러내기 side cutouts, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit
