# 라이츄 (0026 · Raichu) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 0ae6693 · 2026-11-09T00:41:30.223Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다(우리 옷 계열에 없는 것 위주로).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 26 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 844 | `3897b25345d6` | `라이츄_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1074 | `905ee1330229` | `라이츄_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1117 | `c01e3369489c` | `라이츄_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1067 | `4fb38b3bde03` | `라이츄_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1123 | `3e5a1bfcd182` | `라이츄_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1014 | `59adfaa2c1bb` | `라이츄_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1053 | `794cf09ac8dd` | `라이츄_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1102 | `f3bf1ce4e319` | `라이츄_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1066 | `53f9ab622b1d` | `라이츄_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 라이츄_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1147 | `4c143e62675c` | `라이츄_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 요트 갑판 | the cushioned foredeck of a moored yacht |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 자동 — 계열 안에서 장면에 맞게 | a goddess-like draped look inspired by myth — flowing fabric wrapped, knotted and pinned on the body |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 낚싯대 · 낚싯대를 던진다 | casts the line with a fishing rod |

옷 종류 overalls · 옷 색 — · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 걷기 · face_close · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jacket + skirt · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 옆으로 눕기 · waist_up · 옆모습 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 페리 갑판 | the rail of a harbour ferry deck in the wind |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 해적 | a pirate costume — a laced black corset over an off-shoulder white blouse, a ragged mini skirt, thigh-high boots and a tricorn hat |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 blouse + lingerie_set + skirt · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온천 마을 족욕 | a hot-spring town footbath under a wooden roof |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 blouse + traditional · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 평상복 · 얇은 블라우스 + 치마 | a thin blouse and a light skirt |
| 몸 자세 · 구도 | 서기 · environmental · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + skirt · 옷 색 라벤더 · 플럼 (lavender and plum) · 상황 흘러내린 어깨끈 · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · chest_up · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 패션쇼장 | the front row of a fashion show beside a lit runway |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 traditional · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 action
