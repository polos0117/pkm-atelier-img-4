# 도나리 (0049 · Venomoth) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 b55a550 · 2026-11-09T14:15:25.320Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 49 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 904 | `a331f7a63391` | `도나리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 도나리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1096 | `066a39a8ac2b` | `도나리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 도나리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1082 | `31e32dd00f76` | `도나리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 도나리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1021 | `e03b3fa6b678` | `도나리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 도나리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1125 | `697ac917472c` | `도나리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 도나리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1027 | `aa6ab4a0dba1` | `도나리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 도나리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1109 | `1eb33964852c` | `도나리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 도나리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1082 | `69e0f1d3a8e3` | `도나리_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 도나리_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1037 | `37f4211886eb` | `도나리_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 도나리_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1108 | `e272fae42b30` | `도나리_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 온천 · 포켓몬 세계 | an outdoor hot spring of a Pokémon-world mountain town, steam over smooth rocks |
| 하는 일 | 젖은 머리 쓸어넘기기 · 서기 | pushing her wet hair back with both hands |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 수영복 위 유카타 | swimwear with a light yukata worn open over it |

옷 종류 traditional · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 place

## ③ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 해변 · 물가 | a sunny beach with wet sand and shallow surf |
| 하는 일 | 사진 찍기 · 서기 | taking a photo of the scenery with a small camera |
| 의상 계열 | 웨딩 | bridal wear |
| 옷 | 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action

## ④ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 육상 트랙 · 운동 | a running track with lane lines and a grandstand |
| 하는 일 | 몸풀기 · 움직임 | warming up in a forward lunge stretch, both hands resting on her front knee |
| 의상 계열 | 운동복 | activewear made for the activity |
| 옷 | 스포츠 브라 + 레깅스 | a sports bra and high-waisted leggings |

옷 종류 crop_top + leggings · 옷 색 — · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑤ casual4 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 거실 · 집 | her living room with a deep sofa, floor cushions and a low table |
| 하는 일 | 비즈 공예 · 앉기 | threading beads into a small charm with tidy craft tools |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |

옷 종류 blouse + traditional · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 열매 저장고 · 포켓몬 직업 현장 | a cool berry storeroom stacked with padded crates |
| 하는 일 | 도구 정리 · 서기 | tidying her tools and supplies at the end of a shift |
| 의상 계열 | 직업복 | practical clothing for her Pokémon-world job, readable through its tools — her own original workwear — never a copy of an existing trainer, Gym Leader or Pokémon Center uniform |
| 옷 | 사육 작업복 | work overalls over a fitted tank top and rubber boots |

옷 종류 overalls + tank · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 · 나무열매·요리 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 하는 일 | 캠프 카레 끓이기 · 서기 | stirring a pot of berry curry over the camp stove, a ladle in one hand and a bowl ready in the other |
| 의상 계열 | 평상복 | everyday clothes that suit the place and activity |
| 옷 | 니트 + 레깅스 | a chunky knit sweater and leggings |

옷 종류 leggings + sweater · 옷 색 — · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑧ casual7 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 클럽 · 밤 문화 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 하는 일 | 입장 줄 서기 · 서기 | waiting in the queue outside, a short jacket over her shoulders |
| 의상 계열 | 포켓몬 코스튬 | a daring adult costume version of {costume} |
| 옷 | 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 · 화실·공방 | a foley recording booth with microphones and boxes of noisy props |
| 하는 일 | 악기 연습 · 앉기 | practising a small acoustic instrument |
| 의상 계열 | 서브컬처 | a subculture street look |
| 옷 | 이모 | emo — a fitted striped long-sleeve top, a studded belt, skinny jeans and checkered sneakers |

옷 종류 trousers · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 공항 라운지 · 여행지 | an airport lounge — tall windows onto the runway, sleek seats, a long bench and a departures board |
| 하는 일 | 휴대용 게임기 · 앉기 | playing a handheld console, earbuds in |
| 의상 계열 | 역할극·직업 의상 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 옷 | 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 detail
