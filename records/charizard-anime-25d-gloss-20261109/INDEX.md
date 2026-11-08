# 리자몽 (0006 · Charizard) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 2aa37bb · 2026-11-08T17:34:01.923Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 6 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 893 | `d80068ca7844` | `리자몽_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 리자몽_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1049 | `dde6ec7403dd` | `리자몽_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 리자몽_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1163 | `369982d4cb35` | `리자몽_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 리자몽_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1132 | `16015bedb50b` | `리자몽_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 리자몽_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1093 | `1799bdd0b8ff` | `리자몽_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 리자몽_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1065 | `3b1a3052519e` | `리자몽_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 리자몽_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1115 | `fbb795f7e6d1` | `리자몽_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 리자몽_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1056 | `7afced4d3ffb` | `리자몽_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bikini · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 crop_top + overalls · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 레트로 · 90년대 윈드브레이커 + 트랙 팬츠 | a color-blocked 1990s windbreaker with matching track pants |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 jacket + trousers · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 란제리풍 · 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 slip · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 요정 숲 정원 | a misty enchanted garden of moss, ivy and lanterns |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 뒤 3/4 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 action · 직접 입력 scene

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 산장 | a mountain lodge with a front counter and a fireplace |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 호박 | a pumpkin costume — an orange satin corset with a puffed tulle mini skirt, black-and-orange striped thigh-high stockings and a tiny green stem headband |
| 몸 자세 · 구도 | 벽에 기대 서기 · face_close · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + skirt · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit
