# 독파리 (0073 · Tentacruel) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 cd55104 · 2026-11-11T01:57:09.100Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 73 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 916 | `7de52ccbea91` | `독파리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 독파리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1179 | `03699441faea` | `독파리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 독파리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1033 | `a9c423f42909` | `독파리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 독파리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1186 | `5b5740692b50` | `독파리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 독파리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1211 | `3ce50ae3da2a` | `독파리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 독파리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1044 | `5c1ed3e21bfc` | `독파리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 독파리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1230 | `33e8e991f442` | `독파리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 독파리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1088 | `d3f6419fcaaa` | `독파리_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 독파리_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1098 | `96849e6f88fd` | `독파리_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 독파리_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1107 | `a9fc4ef6a063` | `독파리_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 스타디움 | the stands of an open-air Pokémon battle stadium above a marked battle court |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 blouse + traditional · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 침실 | her bedroom, an unmade bed and soft window light |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 옆모습 | kneeling on the ground |
| 손 · 소품 동작 | prop · prop · 편지 · 편지를 두 손으로 읽는다 | reads a handwritten letter held in both hands |

옷 종류 jacket + trousers · 옷 색 — · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 place · 직접 입력 outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 요트 갑판 | the cushioned foredeck of a moored yacht |
| 역할 | — |  |
| 의상 | 동탄룩 · 크롭 니트 + 타이트 미니스커트 | a tight cropped knit top baring the waist and a snug bodycon mini skirt, with high heels |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 낚싯대 · 낚싯대를 어깨에 걸친다 | rests a fishing rod against her shoulder |

옷 종류 knit_top + skirt · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 모험가 · 해적 코르셋 | a pirate look — a loose shirt open at the neck under a laced leather corset, a long sash at the hip, short breeches and tall cuffed boots |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 동전 · 동전을 들어 보인다 | holds a single coin up between two fingers |

옷 종류 lingerie_set + shirt · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 롤러장 | a roller rink under coloured lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 물병 · 물병을 든다 | holds a water bottle at chest height |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | 나무열매 재배자 | a berry grower |
| 의상 | 전통 의상 · 모로코 카프탄 | a Moroccan evening caftan — a long embroidered robe with a decorated belt |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 전지가위 · 전지가위로 잔가지를 친다 | prunes a small branch with a pair of pruning shears |

옷 종류 robe · 옷 색 그레이 · 실버 (dove grey and silver) · 상황 반쯤 푼 차림 · 드러내기 deep V neckline, backless · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 수영복 · 원숄더 수영복 | an asymmetric one-shoulder swimsuit with a clean diagonal neckline |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 swimsuit · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 목욕 차림 · 수영복 위 가운 | a spa robe open over a swimsuit |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 robe + swimsuit · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 place · 직접 입력 scene

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코스프레 행사 | a convention photo zone under ring lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · out |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 light
