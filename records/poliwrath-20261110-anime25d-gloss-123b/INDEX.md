# 강챙이 (0062 · Poliwrath) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5605c25 · 2026-11-09T23:49:09.071Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 62 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 867 | `a2db0d171b67` | `강챙이_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1038 | `d05fa84e9501` | `강챙이_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1142 | `e1aee44f6e4e` | `강챙이_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1168 | `b4738c2559bd` | `강챙이_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1024 | `9e1cb4020e33` | `강챙이_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1114 | `9d5cb82917e8` | `강챙이_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1134 | `a4bcba17563b` | `강챙이_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1077 | `a22cf6da1c91` | `강챙이_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 973 | `ee4e832b8514` | `강챙이_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 강챙이_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1021 | `177cada20b1e` | `강챙이_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 미용실 | a Pokémon grooming salon with a padded grooming platform, brushes and clean towels |
| 역할 | — |  |
| 의상 | 수영복 · 전통 문양 수영복 | a swimsuit in a heritage textile pattern with matching trim |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 리조트 카바나 | a resort cabana with a shaded daybed by the water |
| 역할 | — |  |
| 의상 | 운동복 · 발레 연습복 — 레오타드 + 랩스커트 | a ballet leotard with a short wrap skirt, tights and leg warmers |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · waist_up · 뒤 3/4 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings + skirt · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 평상복 · 롱코트 + 머플러 | a long wool coat and a knitted scarf |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 잔·컵 · 잔을 내려놓는다 | sets a cup down on the surface in front of her |

옷 종류 coat · 옷 색 — · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 거대한 서고 | a vast fantasy library of towering shelves, spiral stairs and floating candles |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 서기 · full_body · 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + traditional · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 자동 — 계열 안에서 장면에 맞게 | a goddess-like draped look inspired by myth — flowing fabric wrapped, knotted and pinned on the body |
| 몸 자세 · 구도 | 걷기 · chest_up · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 걷기 · chest_up · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 케이블카 | a cable car cabin over a misty valley |
| 역할 | — |  |
| 의상 | 홈웨어 · 자동 — 계열 안에서 장면에 맞게 | soft homewear or loungewear |
| 몸 자세 · 구도 | 벽에 기대 서기 · face_close · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + shorts · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 — · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 로데오 카우걸 | a rodeo cowgirl costume — a fringed cropped vest, a western hat, short denim and cowboy boots |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · full_body · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 vest · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 detail
