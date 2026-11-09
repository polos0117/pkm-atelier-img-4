# 페르시온 (0053 · Persian) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 b55a550 · 2026-11-09T14:45:43.242Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 53 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 907 | `51a7593b01b9` | `페르시온_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1059 | `515a33885dfd` | `페르시온_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1120 | `cabc54ebff5c` | `페르시온_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1056 | `79c1cc65ccd8` | `페르시온_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1089 | `0d826c7dfca1` | `페르시온_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1044 | `d3c41399eadf` | `페르시온_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1087 | `e9a6d0d834b3` | `페르시온_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1093 | `ac3561012090` | `페르시온_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1032 | `e618c04bbefa` | `페르시온_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 페르시온_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 997 | `21d2d475a9c1` | `페르시온_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 dress + slip · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, backless · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 저녁 사무실 | a modern glass-walled office at dusk — a desk with a monitor, a swivel chair and city lights beyond the window |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 swimsuit · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코스프레 행사 | a convention photo zone under ring lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 카지노 딜러 | a casino dealer costume with a fitted waistcoat, bow tie and cuffs |
| 몸 자세 · 구도 | 걷기 · waist_up · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 vest · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 장터 | a market street of a Pokémon-world town with awnings and baskets of goods |
| 역할 | — |  |
| 의상 | 직업복 · 사육 작업복 | work overalls over a fitted tank top and rubber boots |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · three_quarter · 정면 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls + tank · 옷 색 아이보리 · 크림 (ivory and warm cream) · 상황 반쯤 푼 차림 · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 장구 아틀리에 | an equipment atelier with saddle pads, travel harnesses and design samples on display |
| 역할 | — |  |
| 의상 | 란제리풍 · 실크 파자마 세트 | a silk pajama set — a short satin camisole with lace trim and matching tap shorts, the long-sleeved pajama shirt worn open over it |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shirt + shorts + tank · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 dress · 옷 색 — · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 무릎 꿇기 · face_close · 3/4 정면 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 양궁장 | an archery range of targets on a green field |
| 역할 | — |  |
| 의상 | 홈웨어 · 아침 로브 | a loosely tied robe |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · full_body · 정면 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 옷 색 — · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 전망대 | a hilltop lookout over a wide valley |
| 역할 | — |  |
| 의상 | 목욕 차림 · 스파 가운 | a plush spa robe tied at the waist |
| 몸 자세 · 구도 | 서기 · full_body · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 light · 직접 입력 outfit
