# 깜놀버슬 (0590 · Foongus) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 93ac493 · 2026-10-31T17:35:36.784Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 590 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 378 | `f55cf4b9680b` | `깜놀버슬_light_glossy_promo_f.webp` |
| ② | heavy | ① 깜놀버슬_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `85845ad61a35` | `깜놀버슬_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 깜놀버슬_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `cf54582cbabd` | `깜놀버슬_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 깜놀버슬_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 251 | `8c041bcfe70e` | `깜놀버슬_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 깜놀버슬_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 257 | `31ad2d52fd7a` | `깜놀버슬_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 깜놀버슬_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 250 | `4ffe8cb8f65e` | `깜놀버슬_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 깜놀버슬_light_glossy_promo_f.webp | `casual1-prompt.txt` | 720 | `70b722d23082` | `깜놀버슬_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 깜놀버슬_light_glossy_promo_f.webp | `casual2-prompt.txt` | 726 | `0a6530c8aaf8` | `깜놀버슬_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 깜놀버슬_light_glossy_promo_f.webp | `casual3-prompt.txt` | 719 | `fcec319efc65` | `깜놀버슬_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 레트로 · 80년대 에어로빅 | an 1980s high-cut aerobics leotard over shiny tights with leg warmers and a headband |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 leggings · 드러내기 side cutouts, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 shirt · 드러내기 side cutouts, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 콘테스트 무대 뒤 | backstage of a Pokémon Contest hall with a rehearsal platform, prop racks and stage lights |
| 역할 | — |  |
| 의상 | 전통 의상 · 유카타 | a light cotton summer yukata wrapped left over right with a soft obi and geta sandals |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 3/4 정면 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 드러내기 high thigh slit, one-shoulder cut · 장면 칸 첫머리 light · 직접 입력 scene, outfit
