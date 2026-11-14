# 쥬피썬더 (0135 · Jolteon) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7492f4c · 2026-11-14T04:08:43.804Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 135 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 887 | `6afd5b6a35cf` | `쥬피썬더_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1204 | `f9b8995ec045` | `쥬피썬더_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1203 | `0aed4118dfc6` | `쥬피썬더_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1148 | `51896551cae6` | `쥬피썬더_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1200 | `c0bdfcd170b0` | `쥬피썬더_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1168 | `c50425417d95` | `쥬피썬더_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1091 | `718e5bcb3ee4` | `쥬피썬더_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1218 | `f604c2b4d408` | `쥬피썬더_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1161 | `48729eb1de6e` | `쥬피썬더_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1087 | `27a9679d1634` | `쥬피썬더_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1108 | `b1fce64a8c12` | `쥬피썬더_anime_25d_gloss_f_casual10.webp` |
| ◆ | casual90 | ① 쥬피썬더_light_anime_25d_gloss_f.webp | `casual90-prompt.txt` | 1111 | `ff6a9e5846df` | `쥬피썬더_anime_25d_gloss_f_casual90.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 트레이너 숙소 휴게실 | a trainers' lodge lounge at night with a fireplace, a small bar counter and wooden tables |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 shorts · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 휴양지 차림 · 랩 점프슈트(짧은) | a wrap-front holiday romper with a deep V neckline and a tie belt |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 갓 구운 나무열매 타르트 · 타르트를 오븐에서 꺼낸다 | lifts a freshly baked berry tart out of the oven in padded mitts |

옷 종류 jumpsuit · 옷 색 레드 · 와인 (deep red and wine) · 상황 넥타이 · 스카프를 풀어 내림 · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 blouse · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 침실 | her bedroom, an unmade bed and soft window light |
| 역할 | — |  |
| 의상 | 홈웨어 · 플리스 상의 + 조거 팬츠 | a soft fleece pullover with relaxed jogger pants |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 sweater + trousers · 옷 색 — · 옷 자유 · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 공원 산책길 | a park path lined with trees and benches |
| 역할 | — |  |
| 의상 | 직업복 · 사육 작업복 | work overalls over a fitted tank top and rubber boots |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 overalls + tank · 옷 색 — · 장면 자유(자유 장면) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 대회 무대 | a contest or tournament stage under spotlights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 dress · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | chin_table · out |  |

옷 종류 dress + robe · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 연습장 | an outdoor battle practice field marked with cones and chalk lines |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 한 발 올려 서기 · environmental · 뒤 3/4 | standing with one foot up on a step, the other leg straight |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 bikini · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 등불을 띄운 강 | a night river covered with floating paper lanterns, stone steps leading down to the water |
| 역할 | — |  |
| 의상 | 란제리풍 · 브라렛 + 하이웨이스트 | a soft-cup bralette with wide straps and matching high-waisted bottoms |
| 몸 자세 · 구도 | 기대 눕기 · three_quarter · 정면 | reclining on her back |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 crop_top · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 detail

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 셀프 세차장 | a self-service car wash bay, a small wet car beside her, a foam bucket, a coiled hose and puddles on the concrete |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 카지노 딜러 | a casino dealer costume with a fitted waistcoat, bow tie and cuffs |
| 몸 자세 · 구도 | 벽에 기대 서기 · full_body · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 vest · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 place

## ◆ casual90 — 캐릭터만의 컷(카페 에너지 에스프레소 전문 · 노출 bold)

일상 열 장에 더하는 한 장 — 채울 칸이 없다. 막히면 같은 지시문으로 두 번 더(모두 세 번), 그래도 막히면 계획기 `--own --own-level` 로 한 단계 내려 다시 짓는다(IMAGE_RULES 3절 「캐릭터만의 컷」).

| 칸 | 표의 글 |
|---|---|
| 장소 | a cozy café — a wooden counter, an espresso machine, glass pastry cases and hanging pendant lamps |
| 장면 | she is an espresso specialist sitting on a stool with her legs crossed, looking over a ceramic coffee cup in one hand |
| 의상 | a barista look fitted to her body — a short café apron over a fitted tank top and short skirt, bare shoulders and legs, a zigzag yellow bolt pin |
| 도구 | a ceramic coffee cup (sig_hold) |
| 자세 추천 | chair_cross_prop |
