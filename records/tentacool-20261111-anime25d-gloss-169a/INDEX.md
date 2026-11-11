# 왕눈해 (0072 · Tentacool) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 e1f0b24 · 2026-11-11T01:11:43.480Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 72 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 906 | `54fd69e3fcd9` | `왕눈해_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1029 | `501a24ccd636` | `왕눈해_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1184 | `021a4e669116` | `왕눈해_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1049 | `a26a575c8d16` | `왕눈해_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1165 | `c55bb92ce552` | `왕눈해_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1031 | `8b8e819558b7` | `왕눈해_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1107 | `e7e91a2b1c43` | `왕눈해_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1059 | `f9f0bfcb6c89` | `왕눈해_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1063 | `cb7eda16eba7` | `왕눈해_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 왕눈해_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 991 | `02e61ce9719f` | `왕눈해_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사막 길 | a wind-rippled desert dune trail |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 마녀 | a dark witch costume — a plunging black velvet bodysuit under a sheer black chiffon cape, a crooked wide-brimmed pointed hat and sheer thigh-high stockings |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 종이 지도 · 지도를 두 손으로 펼친다 | unfolds a folded paper map in both hands in front of her |

옷 종류 bodysuit + coat · 옷 색 — · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 place · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 저녁 사무실 | a modern glass-walled office at dusk — a desk with a monitor, a swivel chair and city lights beyond the window |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 jumpsuit · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 새 포켓몬 보호소 | a spacious aviary with high perches and woven nest boxes |
| 역할 | — |  |
| 의상 | 직업복 · 자동 — 계열 안에서 장면에 맞게 | practical clothing for her Pokémon-world job, readable through its tools |
| 몸 자세 · 구도 | 바닥에 앉기 · face_close · 옆모습 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls + tank · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 트레이너 숙소 휴게실 | a trainers' lodge lounge at night with a fireplace, a small bar counter and wooden tables |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 서기 · full_body · 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 흘러내린 어깨끈 · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 니트 | an off-shoulder knit top slipping from one shoulder over shorts |
| 몸 자세 · 구도 | 의자에 앉기 · waist_up · 뒤 3/4 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + shorts · 옷 색 — · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 대리석 목욕궁 | a Roman marble bath hall — columns, mosaic floors and a wide steaming pool lit from high windows |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · full_body · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 서기 · waist_up · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 란제리풍 · 앞 끈 코르셋 | a front-lacing corset over matching high-waisted bottoms |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 뒤 3/4 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 light
