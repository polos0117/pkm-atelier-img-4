# 리자드 (0005 · Charmeleon) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 cdc4ca3 · 2026-11-08T17:26:45.475Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 5 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 858 | `935ff1f66e42` | `리자드_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 리자드_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1118 | `dea079de2042` | `리자드_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 리자드_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1122 | `c0083118b5cb` | `리자드_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 리자드_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 987 | `76c7cf5da308` | `리자드_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 리자드_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 996 | `e9a6f4eac438` | `리자드_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 리자드_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1070 | `a94ab3019233` | `리자드_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 리자드_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1066 | `4943210b7acc` | `리자드_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 리자드_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1059 | `40f339af82dc` | `리자드_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 robe + slip · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 로토무 제품 쇼룸 | a bright design showroom of household appliance prototypes |
| 역할 | — |  |
| 의상 | 평상복 · 롱코트 + 머플러 | a long wool coat and a knitted scarf |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 coat · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 목욕 차림 · 수영복 위 가운 | a spa robe open over a swimsuit |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · full_body · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe + swimsuit · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 바닥에 앉기 · full_body · 뒤 3/4 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 런웨이 | a fashion runway under white spotlights |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 걷기 · chest_up · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + shirt · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · chest_up · 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 vest · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 수영복 · 홀터 비키니 | a halter bikini with a neck tie and an underbust band |
| 몸 자세 · 구도 | 의자에 앉기 · waist_up · 뒤 3/4 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 action
