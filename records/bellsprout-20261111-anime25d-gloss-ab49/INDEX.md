# 모다피 (0069 · Bellsprout) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7d2c433 · 2026-11-10T17:27:33.781Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 69 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 896 | `4015c3fc133c` | `모다피_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 모다피_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1021 | `f2fb26e30998` | `모다피_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 모다피_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1102 | `9a95fea7bbdc` | `모다피_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 모다피_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1004 | `185927fc605b` | `모다피_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 모다피_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1105 | `6f78fb302fb4` | `모다피_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 모다피_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1193 | `6ffdc8e5a39e` | `모다피_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 모다피_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1060 | `2cf225b52c7e` | `모다피_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 모다피_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1041 | `6c6d7d430e63` | `모다피_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 모다피_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1194 | `9946beddf2bd` | `모다피_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 모다피_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1150 | `02b75654b095` | `모다피_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 요정 무도회 | a fae ball costume — a backless gown with a wing-shaped satin cape and a leaf mask |
| 몸 자세 · 구도 | 서기 · three_quarter · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 coat + dress · 옷 색 — · 드러내기 plunging neckline, backless · 장면 칸 첫머리 action · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 목장 | a sunny ranch — a weathered wooden fence, hay bales and horses grazing in the distance |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 카지노 딜러 | a casino dealer costume with a fitted waistcoat, bow tie and cuffs |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 vest · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 강가 선착장 | a wooden river dock above calm water |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · face_close · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 평상복 · 홀터 탑 + 짧은 반바지 | a halter top and short shorts |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 shorts · 옷 색 — · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 공중 정원 | a floating sky garden of hanging vines and flowering terraces above the clouds |
| 역할 | — |  |
| 의상 | 화보 쿠튀르 · 레트로 퓨처 점프수트 | a sleek retro-futurist jumpsuit with vintage trim |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 jumpsuit · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 부두 | a harbor ferry dock beside a small village parcel station |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + traditional · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 직업복 · 글래머 앞치마 룩 | a sleek fitted wrap dress under a crisp short apron |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · full_body · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron + dress · 옷 색 스카이 · 네이비 (sky blue and navy) · 상황 바람에 날림 · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · out |  |

옷 종류 traditional · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 detail
