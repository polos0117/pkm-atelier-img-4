# 가디 (0058 · Growlithe) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 31a3839 · 2026-11-09T16:06:29.367Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 58 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 911 | `07d2d385d04f` | `가디_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 가디_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1058 | `88ab36f8d394` | `가디_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 가디_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1146 | `fef02f1c9997` | `가디_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 가디_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 998 | `882553f6eee0` | `가디_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 가디_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1017 | `b8b2dc15671b` | `가디_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 가디_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1100 | `d1d8110ed061` | `가디_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 가디_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1016 | `814b2e3fd80d` | `가디_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 가디_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1098 | `19bf573dc9d7` | `가디_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 가디_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1099 | `cb847f120396` | `가디_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 가디_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1128 | `7f711b055f8b` | `가디_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · waist_up · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 — · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 바닷가 산책길 | a rocky coast path with tide pools |
| 역할 | — |  |
| 의상 | 동탄룩 · 클럽 — 메탈릭 슬립 미니 | a club outfit — a liquid-metallic cowl-neck slip mini dress with thin straps and strappy heels |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 dress + slip · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 롤러장 | a roller rink under coloured lights |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 서기 · full_body · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse · 옷 색 — · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 요정 무도회 | a fae ball costume — a backless gown with a wing-shaped satin cape and a leaf mask |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 coat + dress · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 밤 천문대 | a night observatory under an open dome |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · waist_up · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 레트로 우주비행사 | a retro space-age costume — a fitted white jumpsuit with silver trim and moon boots |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · full_body · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 스타디움 | the stands of an open-air Pokémon battle stadium above a marked battle court |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 의자에 앉기 · chest_up · 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 물가 연구 기지 | a calm lake pier and shoreline research base with a small moored boat |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 걷기 · chest_up · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 직업복 · 사육 작업복 | work overalls over a fitted tank top and rubber boots |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 뒤 3/4 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls + tank · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 light
