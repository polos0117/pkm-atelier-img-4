# 우츠동 (0070 · Weepinbell) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 30e226d · 2026-11-10T23:17:38.190Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 70 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 903 | `5acd0191605d` | `우츠동_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1175 | `e8c82afef03a` | `우츠동_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1041 | `7abfb56043cf` | `우츠동_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1254 | `62bbb6668be8` | `우츠동_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1120 | `98fdc1408754` | `우츠동_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1056 | `1d7002892f78` | `우츠동_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1009 | `d66c62bf0aa0` | `우츠동_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1165 | `9195f7e5ab72` | `우츠동_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1052 | `69499ed26f94` | `우츠동_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 우츠동_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1074 | `74a642f0955c` | `우츠동_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 장터 | a market street of a Pokémon-world town with awnings and baskets of goods |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 lingerie_set + shirt · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 침실 | her bedroom, an unmade bed and soft window light |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 overalls · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 히노키 탕 | a cedar-wood tub by the window of a mountain inn |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 자동 — 계열 안에서 장면에 맞게 | a goddess-like draped look inspired by myth — flowing fabric wrapped, knotted and pinned on the body |
| 몸 자세 · 구도 | 걷기 · full_body · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + shorts · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 옆모습 | reclining on her back |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 레드카펫·시상식 | a red carpet and award hall with camera flashes |
| 역할 | — |  |
| 의상 | 평상복 · 롱코트 + 머플러 | a long wool coat and a knitted scarf |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 선글라스 · 접은 선글라스를 든다 | holds folded a pair of sunglasses by one arm |

옷 종류 coat · 옷 색 — · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 숲길 | a forest trail junction with a wooden marker |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shorts + tank · 옷 색 라벤더 · 플럼 (lavender and plum) · 상황 흘러내린 어깨끈 · 드러내기 plunging neckline, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 동반 호텔 | the reception counter of a Pokémon-friendly hotel |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · full_body · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shirt · 옷 색 — · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 action · 직접 입력 outfit
