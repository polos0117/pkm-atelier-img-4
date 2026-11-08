# 피죤 (0017 · Pidgeotto) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 80ab039 · 2026-11-08T21:17:49.865Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 17 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 854 | `36be79ec8f6a` | `피죤_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 피죤_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1158 | `37d2d4083b8d` | `피죤_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 피죤_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1119 | `8e496ce89239` | `피죤_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 피죤_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1100 | `4c6016e1e116` | `피죤_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 피죤_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1030 | `adf67ce2fe58` | `피죤_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 피죤_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1008 | `1ec7c875b440` | `피죤_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 피죤_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1088 | `fec39556d89f` | `피죤_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 피죤_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 972 | `fc78977fbcdf` | `피죤_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 피죤_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1051 | `df3ad1335cf0` | `피죤_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 피죤_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1071 | `32b8069295c9` | `피죤_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 새 포켓몬 보호소 | a spacious aviary with high perches and woven nest boxes |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 swimsuit · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 blouse · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 자동 — 계열 안에서 장면에 맞게 | a goddess-like draped look inspired by myth — flowing fabric wrapped, knotted and pinned on the body |
| 몸 자세 · 구도 | 의자에 앉기 · chest_up · 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 웨딩 · 자동 — 계열 안에서 장면에 맞게 | bridal wear |
| 몸 자세 · 구도 | 걷기 · full_body · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 라벤더 · 플럼 (lavender and plum) · 상황 흘러내린 어깨끈 · 드러내기 deep V neckline, backless · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호숫가 | a lakeside of flat rocks and still water |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 uniform · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 동탄룩 · 자동 — 계열 안에서 장면에 맞게 | a body-hugging, curve-tracing going-out outfit in the Korean 'Dongtan look' style |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | pet_companion · floor_brace |  |

옷 종류 jumpsuit · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 — · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · chest_up · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 action
