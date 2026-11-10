# 윤겔라 (0064 · Kadabra) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7d2c433 · 2026-11-10T17:27:09.429Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 64 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 941 | `a278025f4ade` | `윤겔라_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1192 | `5c26bb677697` | `윤겔라_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1047 | `bea19994906e` | `윤겔라_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1170 | `235228d89e42` | `윤겔라_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1179 | `b65188a87ff0` | `윤겔라_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1104 | `53d251af71d7` | `윤겔라_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1002 | `ef2acddc5874` | `윤겔라_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1154 | `f0feddb0c449` | `윤겔라_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1010 | `318b14e4372c` | `윤겔라_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 윤겔라_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 998 | `4f3ece6d9a89` | `윤겔라_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 직업복 · 자동 — 계열 안에서 장면에 맞게 | practical clothing for her Pokémon-world job, readable through its tools |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 shirt + trousers · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 패션쇼장 | the front row of a fashion show beside a lit runway |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 blouse + traditional · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 공중 정원 | a floating sky garden of hanging vines and flowering terraces above the clouds |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 해골 | a skeleton costume — a black stretch catsuit printed with white bones, worn with a red-rose flower crown |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 등불 · 등불을 들어 비춘다 | lifts a small hand lantern to chest height |

옷 종류 bodysuit · 옷 색 — · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬센터 로비 | the bright lobby of a Pokémon Center with a reception counter, sofas and potted plants |
| 역할 | — |  |
| 의상 | 모험가 · 비행사 | a vintage aviatrix look — a cropped leather flight jacket over a fitted top, high-waisted jodhpurs, goggles pushed up on her head and tall boots |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 jacket · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 체육관·복싱장 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 역할 | — |  |
| 의상 | 홈웨어 · 아침 로브 | a loosely tied robe |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | wave · down |  |

옷 종류 robe · 옷 색 민트 · 틸 (mint and teal) · 상황 반쯤 푼 차림 · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | hip · hair_tuck |  |

옷 종류 lingerie_set · 옷 색 — · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 부두 | a harbor ferry dock beside a small village parcel station |
| 역할 | — |  |
| 의상 | 수영복 · 컷아웃 원피스 | a fully lined one-piece swimsuit with large cut-outs at the sides of the waist |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 swimsuit · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · full_body · 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · environmental · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 detail
