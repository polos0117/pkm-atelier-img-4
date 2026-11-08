# 뿔충이 (0013 · Weedle) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 106d730 · 2026-11-08T23:51:13.763Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 13 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 829 | `e7b4c7dd7233` | `뿔충이_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1010 | `e07a822232cb` | `뿔충이_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1150 | `ee982c4c3c27` | `뿔충이_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1069 | `5c1e3ccbbd31` | `뿔충이_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1065 | `fe83cf84d7c4` | `뿔충이_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1106 | `495030660612` | `뿔충이_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1093 | `a01fc2015e69` | `뿔충이_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1130 | `632de118a50e` | `뿔충이_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1022 | `dc96d4a3b542` | `뿔충이_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1130 | `2cad5c2c7c26` | `뿔충이_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 겨울 산장 테라스 | a snowy mountain-lodge terrace with a wooden railing and benches above a winter valley |
| 역할 | — |  |
| 의상 | 란제리풍 · 벨벳 세트 | a deep-coloured velvet bralette and high-waisted bottoms |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 토트백 · 가방끈을 어깨에 걸쳐 잡는다 | holds the strap of a canvas tote bag on her shoulder |

옷 종류 crop_top · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 비키니 | a 1950s pin-up bikini with a high-waisted bottom and a halter top |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bikini · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 흘러내린 어깨끈 · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 3/4 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + leggings · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · environmental · 뒤 3/4 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 수중 궁전 | an underwater palace hall behind great glass arches, a sweeping coral-stone staircase, rippling blue light and drifting bubbles outside |
| 역할 | — |  |
| 의상 | 화보 쿠튀르 · 자동 — 계열 안에서 장면에 맞게 | an editorial couture look whose cut and tailoring read clearly |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · face_close · 3/4 정면 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + trousers · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 쇼핑몰 | a shopping mall atrium with a fountain and glass railings |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 아이스크림 · 아이스크림을 먹는다 | brings an ice cream cone to her lips |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 자동 — 계열 안에서 장면에 맞게 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 dress · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 스타디움 | the stands of an open-air Pokémon battle stadium above a marked battle court |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 걷기 · full_body · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 코트 | an outdoor court for tennis or basketball |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 leggings + sweater · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 action
