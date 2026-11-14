# 메가니움 (0154 · Meganium) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 e7016d3 · 2026-11-14T11:08:16.753Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 154 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 911 | `fe05b3fd196e` | `메가니움_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1208 | `e40a481c75cc` | `메가니움_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1154 | `44d863b28721` | `메가니움_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1172 | `f7f1b4427d80` | `메가니움_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1119 | `0b90e52990fe` | `메가니움_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1175 | `e64ecdae33df` | `메가니움_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1051 | `6024aa550830` | `메가니움_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1162 | `1ff03de8f6c3` | `메가니움_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1210 | `85db7862810a` | `메가니움_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1175 | `7f6216960b4a` | `메가니움_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1168 | `5eed3fb5020a` | `메가니움_anime_25d_gloss_f_casual10.webp` |
| ◆ | casual90 | ① 메가니움_light_anime_25d_gloss_f.webp | `casual90-prompt.txt` | 1076 | `ca2fadbbc7e6` | `메가니움_anime_25d_gloss_f_casual90.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 잘 익은 나무열매 · 가지에서 나무열매를 딴다 | picks a ripe berry from a low branch |

옷 종류 apron + shirt · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 공연장 대기실 | a backstage dressing room with a bulb-lit mirror, a vanity table and costume racks |
| 역할 | — |  |
| 의상 | 홈웨어 · 플리스 상의 + 조거 팬츠 | a soft fleece pullover with relaxed jogger pants |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 수건 · 수건을 안는다 | holds a towel folded against her chest |

옷 종류 sweater + trousers · 옷 색 — · 장면 자유(자유 장면) · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 손거울 · 손거울을 본다 | holds a compact mirror open in front of her face |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 카지노 딜러 | a casino dealer costume with a fitted waistcoat, bow tie and cuffs |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 vest · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 기대 눕기 · waist_up · 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 수건 · 수건을 안는다 | holds a towel folded against her chest |

옷 종류 traditional · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 강가 선착장 | a wooden river dock above calm water |
| 역할 | — |  |
| 의상 | 휴양지 차림 · 랩 점프슈트(짧은) | a wrap-front holiday romper with a deep V neckline and a tie belt |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 3/4 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 jumpsuit · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 모험가 · 사파리 원피스 | a safari look — a belted khaki shirt dress with a short hem, a wide-brim hat and tall lace-up boots |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 닦는 천 · 앞의 면을 천으로 닦는다 | wipes the surface in front of her with a folded cleaning cloth |

옷 종류 dress + shirt · 옷 색 — · 옷 자유 · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 한쪽 무릎 꿇기 · face_close · 옆모습 | kneeling on one knee, the other foot planted flat in front of her |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 bodysuit + leggings · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 사막 오아시스 | a desert oasis at golden hour — date palms, a still turquoise pool and silk tents on the dunes |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 등불 · 등불을 든다 | holds a small hand lantern low at her side |

옷 종류 blouse + traditional · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 action

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 빨래터 | a washing place by a water channel of a Pokémon-world town, stone basins, drying lines overhead and wet flagstones |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 닦는 천 · 천을 든다 | holds a folded cleaning cloth at chest height |

옷 종류 robe + slip · 옷 색 스카이 · 네이비 (sky blue and navy) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 place

## ◆ casual90 — 캐릭터만의 컷(허브티 가게 점장 · 노출 bold)

일상 열 장에 더하는 한 장 — 채울 칸이 없다. 막히면 같은 지시문으로 두 번 더(모두 세 번), 그래도 막히면 계획기 `--own --own-level` 로 한 단계 내려 다시 짓는다(IMAGE_RULES 3절 「캐릭터만의 컷」).

| 칸 | 표의 글 |
|---|---|
| 장소 | an herbal tea shop — jars of dried leaves, hanging herb bundles, a copper kettle, a wooden counter with a small scale |
| 장면 | she is the tea shop manager standing by the counter with her hands clasped in front, welcoming everyone with a gentle smile |
| 의상 | a tea shop clerk look fitted to her body — a green apron over a fitted strappy top and short skirt, bare shoulders and legs, a large pink flower pinned at her collar |
| 도구 | — |
| 자세 추천 | clasp_low |
