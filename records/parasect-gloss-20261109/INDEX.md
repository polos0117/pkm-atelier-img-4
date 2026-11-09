# 파라섹트 (0047 · Parasect) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 87e324d · 2026-11-09T13:43:26.644Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 47 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 872 | `1b387ba30177` | `파라섹트_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1161 | `2bb4353878c9` | `파라섹트_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1008 | `19aa8adb1879` | `파라섹트_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1112 | `aac7c0bacee1` | `파라섹트_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1154 | `af767fa70f38` | `파라섹트_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1054 | `30b92889278c` | `파라섹트_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1075 | `42fccb0cf60c` | `파라섹트_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1098 | `ef533d1b5478` | `파라섹트_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1026 | `8a7f5f113eed` | `파라섹트_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 파라섹트_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1016 | `144fa346b176` | `파라섹트_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 내 방 | her own room in a small house of a Pokémon-world town, a shelf of travel gear by the window |
| 역할 | — |  |
| 의상 | 동탄룩 · 자동 — 계열 안에서 장면에 맞게 | a body-hugging, curve-tracing going-out outfit in the Korean 'Dongtan look' style |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 knit_top + skirt · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 vest · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 robe + slip · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 박물관 | a Pokémon natural-history museum with display stands, a gallery and an archive room |
| 역할 | — |  |
| 의상 | 평상복 · 롱코트 + 머플러 | a long wool coat and a knitted scarf |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 coat · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 dress · 옷 색 — · 드러내기 plunging neckline, backless · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호숫가 | a lakeside of flat rocks and still water |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 blouse · 옷 색 민트 · 틸 (mint and teal) · 상황 반쯤 푼 차림 · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 란제리풍 · 실크 파자마 세트 | a silk pajama set — a short satin camisole with lace trim and matching tap shorts, the long-sleeved pajama shirt worn open over it |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 shirt + shorts + tank · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 공중 정원 | a floating sky garden of hanging vines and flowering terraces above the clouds |
| 역할 | — |  |
| 의상 | 수영복 · 컷아웃 원피스 | a fully lined one-piece swimsuit with large cut-outs at the sides of the waist |
| 몸 자세 · 구도 | 쪼그려 앉기 · environmental · 옆모습 | crouching low on her heels |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shirt · 옷 색 — · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 place · 직접 입력 outfit
