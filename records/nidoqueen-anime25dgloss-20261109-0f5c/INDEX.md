# 니드퀸 (0031 · Nidoqueen) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 42f87ea · 2026-11-09T05:03:54.473Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 31 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 870 | `1c0069c7600e` | `니드퀸_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1150 | `9d81638dfb0c` | `니드퀸_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1039 | `c0ddfba6157c` | `니드퀸_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1104 | `c05dbba8894a` | `니드퀸_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1117 | `9dfa8e20785a` | `니드퀸_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1012 | `a86c2ddc9a23` | `니드퀸_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1076 | `1a3cf0b42216` | `니드퀸_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 977 | `9b8b9b46ff10` | `니드퀸_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1029 | `7f7444ecb7c6` | `니드퀸_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 니드퀸_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1054 | `4e5ce79d2b96` | `니드퀸_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 모험가 · 사파리 원피스 | a safari look — a belted khaki shirt dress with a short hem, a wide-brim hat and tall lace-up boots |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 dress + shirt · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 아라비안 나이트 | an Arabian-nights look — a jewelled cropped top, a sheer veil scarf over the shoulders, low-slung flowing chiffon trousers and gold coin anklets |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 노트와 펜 · 노트에 쓴다 | writes in a notebook with a pen on the table |

옷 종류 crop_top + trousers · 옷 색 — · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 light · 직접 입력 outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, open back · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 강가 선착장 | a wooden river dock above calm water |
| 역할 | — |  |
| 의상 | 홈웨어 · 크롭 후디 + 쇼츠 | a cropped hoodie and short shorts |
| 몸 자세 · 구도 | 물에 몸 담그기 · waist_up · 정면 | chest-deep in the water |
| 손 · 소품 동작 | hair_tuck · water_trail |  |

옷 종류 shorts + sweater · 옷 색 — · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 수영복 · 컷아웃 원피스 | a fully lined one-piece swimsuit with large cut-outs at the sides of the waist |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 swimsuit · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 robe + slip · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 시골 역 | a small rural station with a wooden bench and a single platform |
| 역할 | — |  |
| 의상 | 동탄룩 · 크롭 니트 + 타이트 미니스커트 | a tight cropped knit top baring the waist and a snug bodycon mini skirt, with high heels |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + skirt · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 축제 거리 | a festival street of lanterns, food stalls and paper decorations |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 열차 객실 | a carriage of a Pokémon travel train with luggage racks and resting cushions |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action
