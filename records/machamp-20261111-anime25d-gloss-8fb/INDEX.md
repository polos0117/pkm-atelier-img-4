# 괴력몬 (0068 · Machamp) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 30e226d · 2026-11-10T23:14:08.312Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 68 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 889 | `7221a51cb163` | `괴력몬_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1206 | `5b8fef33f142` | `괴력몬_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1226 | `09e7b488058b` | `괴력몬_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1117 | `fcec60c203a8` | `괴력몬_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1012 | `bc5427b79990` | `괴력몬_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1178 | `9599f7bf83de` | `괴력몬_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1044 | `cc6c4d959a81` | `괴력몬_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1141 | `41715b3ea57f` | `괴력몬_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1153 | `4def575d001f` | `괴력몬_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 괴력몬_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1095 | `6354c21ee26b` | `괴력몬_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 내 방 | her own room in a small house of a Pokémon-world town, a shelf of travel gear by the window |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 빗 · 머리를 빗는다 | brushes her hair with a hairbrush |

옷 종류 swimsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 잔·컵 · 잔을 입에 댄다 | brings a cup to her lips |

옷 종류 jacket + trousers · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 히노키 탕 | a cedar-wood tub by the window of a mountain inn |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 슬립 | a bias-cut satin slip with narrow straps and a straight hem |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 slip · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 한쪽 어깨 여신 | a one-shoulder goddess gown of flowing chiffon gathered at one shoulder with a gold brooch, the other shoulder and arm bare, a thigh-high slit |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 dress · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 vest · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 산장 | a mountain lodge with a front counter and a fireplace |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress + robe · 옷 색 아이보리 · 크림 (ivory and warm cream) · 상황 반쯤 푼 차림 · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 | a covered porch on a rainy day, umbrellas resting by the door |
| 역할 | — |  |
| 의상 | 전통 의상 · 한복 · 정장 | a formal Korean hanbok — short jeogori with goreum bow and white dongjeong collar over a full high-wrapped chima; not hanfu |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · environmental · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 옷 색 — · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 동탄룩 · 크롭 니트 + 타이트 미니스커트 | a tight cropped knit top baring the waist and a snug bodycon mini skirt, with high heels |
| 몸 자세 · 구도 | 쪼그려 앉기 · waist_up · 뒤 3/4 | crouching low on her heels |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + skirt · 옷 색 — · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 detail · 직접 입력 outfit
