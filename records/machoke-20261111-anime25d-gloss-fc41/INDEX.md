# 근육몬 (0067 · Machoke) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 cc8c3b5 · 2026-11-10T21:37:22.099Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 67 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 876 | `d3e241c79ef8` | `근육몬_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1117 | `f9245f3b0d7d` | `근육몬_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1122 | `010017a33352` | `근육몬_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1048 | `eaa268264474` | `근육몬_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1129 | `74c8ce4f4bbf` | `근육몬_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1125 | `dfc924e7f705` | `근육몬_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1083 | `f406f8d974fa` | `근육몬_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1045 | `36c3263e5b97` | `근육몬_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1036 | `337b62d6f5bf` | `근육몬_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 근육몬_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1001 | `d351354f9382` | `근육몬_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 전통 의상 · 살와르 카미즈 | a daily salwar kameez — a long tunic with side slits over loose salwar trousers and a light dupatta |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 trousers · 옷 색 — · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 자동 — 계열 안에서 장면에 맞게 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · out |  |

옷 종류 vest · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 action · 직접 입력 outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 해변 | a sunny beach with wet sand and shallow surf |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 dress · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 양궁장 | an archery range of targets on a green field |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 cardigan + leggings · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 | a village market stall piled with fresh berries |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 평상복 · 물감 묻은 셔츠 | a paint-splattered oversized shirt over shorts |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · full_body · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shirt + shorts · 옷 색 세이지 · 올리브 (sage and olive green) · 상황 바람에 날림 · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 거실 | her living room with a deep sofa, floor cushions and a low table |
| 역할 | — |  |
| 의상 | 서브컬처 · 이모 | emo — a fitted striped long-sleeve top, a studded belt, skinny jeans and checkered sneakers |
| 몸 자세 · 구도 | 엎드리기 · environmental · 옆모습 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 trousers · 옷 색 — · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 홀터 플레이수트 | a 1950s halter playsuit |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 옆모습 | kneeling on the ground |
| 손 · 소품 동작 | prop · prop · 게임 패드 · 게임을 한다 | plays with a game controller in both hands, thumbs on the sticks |

옷 종류 jumpsuit · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 벽에 기대 서기 · full_body · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 — · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 outfit
