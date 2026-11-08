# 별가사리 (0120 · Staryu) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bab0bad · 2026-11-08T23:02:10.094Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 120 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 828 | `7e477fa374a2` | `별가사리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1027 | `7126fa3adddf` | `별가사리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1121 | `7ff6955a2260` | `별가사리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 976 | `dcffe33be115` | `별가사리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1032 | `06e7afa46905` | `별가사리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1052 | `95f887197a8d` | `별가사리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1134 | `cb513d5a40a4` | `별가사리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1176 | `bb1062d839ce` | `별가사리_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1046 | `d0b37d7e5d0d` | `별가사리_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 별가사리_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1059 | `9bc6f52e7131` | `별가사리_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 | a village market stall piled with fresh berries |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 장터 | a market street of a Pokémon-world town with awnings and baskets of goods |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · face_close · 옆모습 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 롤러장 | a roller rink under coloured lights |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · three_quarter · 옆모습 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 의자에 앉기 · chest_up · 옆모습 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 — · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 케이블카 | a cable car cabin over a misty valley |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 공원 산책길 | a park path lined with trees and benches |
| 역할 | — |  |
| 의상 | 동탄룩 · 자동 — 계열 안에서 장면에 맞게 | a body-hugging, curve-tracing going-out outfit in the Korean 'Dongtan look' style |
| 몸 자세 · 구도 | 걷기 · waist_up · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 침실 | her bedroom, an unmade bed and soft window light |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 무릎 꿇기 · full_body · 뒤 3/4 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse · 옷 색 블랙 · 차콜 (black with charcoal accents) · 상황 반쯤 푼 차림 · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 승무원풍 | a retro flight-attendant-inspired costume with a fitted jacket, scarf and original airline-style trim |
| 몸 자세 · 구도 | 엎드리기 · full_body · 뒤 3/4 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jacket · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 란제리풍 · 자동 — 계열 안에서 장면에 맞게 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 몸 자세 · 구도 | 서기 · waist_up · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 light
