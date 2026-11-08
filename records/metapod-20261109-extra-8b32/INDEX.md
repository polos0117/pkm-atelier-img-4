# 단데기 (0011 · Metapod) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bab0bad · 2026-11-08T23:21:55.843Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 11 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 817 | `e850352c102e` | `단데기_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 단데기_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1048 | `66c4324804ff` | `단데기_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 단데기_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1094 | `d5ac23c4de7e` | `단데기_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 단데기_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 994 | `38e012a6974d` | `단데기_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 단데기_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 970 | `ec0f959e89ad` | `단데기_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 단데기_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 986 | `c9a05683c836` | `단데기_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 단데기_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1139 | `db00aead3b22` | `단데기_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 단데기_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1066 | `04ae9060970b` | `단데기_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 단데기_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1073 | `9279bf65eec5` | `단데기_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 단데기_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1120 | `78d86d3a8b35` | `단데기_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사막 길 | a wind-rippled desert dune trail |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 엎드리기 · chest_up · 옆모습 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 강가 선착장 | a wooden river dock above calm water |
| 역할 | — |  |
| 의상 | 모험가 · 비행사 | a vintage aviatrix look — a cropped leather flight jacket over a fitted top, high-waisted jodhpurs, goggles pushed up on her head and tall boots |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 jacket · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코트 | an outdoor court for tennis or basketball |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 니트 | an off-shoulder knit top slipping from one shoulder over shorts |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + shorts · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · three_quarter · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코스프레 행사 | a convention photo zone under ring lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 — · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 직업복 · 자동 — 계열 안에서 장면에 맞게 | practical clothing for her Pokémon-world job, readable through its tools |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 슬립 | a bias-cut satin slip with narrow straps and a straight hem |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · three_quarter · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 미용실 | a Pokémon grooming salon with a padded grooming platform, brushes and clean towels |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 숲의 정령 | a forest spirit costume — a moss-green draped gown with a flower crown and trailing ivy |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · full_body · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 세이지 · 올리브 (sage and olive green) · 상황 바람에 날림 · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 거실 | her living room with a deep sofa, floor cushions and a low table |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 시스루 유령 | a sheer ghost costume — layers of translucent white chiffon draped over a short white satin slip |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · face_close · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 action
