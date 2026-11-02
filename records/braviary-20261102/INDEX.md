# 워글 (0628 · Braviary) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 dab49a6 · 2026-11-02T11:42:12.610Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 628 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 401 | `5ec1819592a7` | `워글_light_glossy_promo_f.webp` |
| ② | heavy | ① 워글_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `667d47a55f8b` | `워글_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 워글_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `94434f1b4778` | `워글_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 워글_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `109be0bfab24` | `워글_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 워글_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `61db93e777b3` | `워글_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 워글_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `35bd6310d20a` | `워글_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 워글_light_glossy_promo_f.webp | `casual1-prompt.txt` | 646 | `c4b0067d0775` | `워글_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 워글_light_glossy_promo_f.webp | `casual2-prompt.txt` | 729 | `650b9b446d21` | `워글_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 워글_light_glossy_promo_f.webp | `casual3-prompt.txt` | 771 | `42d30c6483e6` | `워글_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 crop_top + skirt · 드러내기 cropped hem, mini length · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 요정 숲 정원 | a misty enchanted garden of moss, ivy and lanterns |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 apron · 드러내기 halter neck, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 트레이너 숙소 휴게실 | a trainers' lodge lounge at night with a fireplace, a small bar counter and wooden tables |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · face_close · 옆모습 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
