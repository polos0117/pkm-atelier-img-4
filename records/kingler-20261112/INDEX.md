# 킹크랩 (0099 · Kingler) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 09e6f77 · 2026-11-12T12:40:01.583Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 99 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 885 | `abc4c98db357` | `킹크랩_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1110 | `305aad4c3967` | `킹크랩_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1154 | `237ef401a602` | `킹크랩_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1089 | `00cf24dda1ae` | `킹크랩_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1123 | `2c0bdfadfd63` | `킹크랩_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1114 | `c28f5a7ca96e` | `킹크랩_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1076 | `38e426b957f7` | `킹크랩_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1208 | `17c643c5e676` | `킹크랩_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1111 | `e95d714652a5` | `킹크랩_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1169 | `0f9c0900b48b` | `킹크랩_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 킹크랩_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1054 | `d7c7ec23e5c0` | `킹크랩_anime_25d_gloss_f_casual10.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코트 | an outdoor court for tennis or basketball |
| 역할 | — |  |
| 의상 | 평상복 · 홀터 탑 + 짧은 반바지 | a halter top and short shorts |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 수건 · 목에 건 수건 끝을 잡는다 | holds one end of a towel hung around her neck |

옷 종류 shorts · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 | a city rooftop with a water tank, string lights and the skyline |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 카지노 딜러 | a casino dealer costume with a fitted waistcoat, bow tie and cuffs |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 토트백 · 가방끈을 어깨에 걸쳐 잡는다 | holds the strap of a canvas tote bag on her shoulder |

옷 종류 vest · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 목장 | a sunny ranch — a weathered wooden fence, hay bales and horses grazing in the distance |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 dress + slip · 옷 색 라벤더 · 플럼 (lavender and plum) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 레트로 퓨처 집 | a retro-futurist home of rounded chrome appliances and soft panels |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 새 포켓몬 보호소 | a spacious aviary with high perches and woven nest boxes |
| 역할 | 새 포켓몬 보호소 사육사 | a Bird-Pokémon sanctuary keeper |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 엮은 둥지 상자 · 둥지 상자를 높은 횃대에 올린다 | reaches up to settle a woven nest box on a high perch |

옷 종류 blouse + traditional · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 테마 행사장 | a themed costume event venue with props and a photo wall |
| 역할 | — |  |
| 의상 | 수영복 · 전통 문양 수영복 | a swimsuit in a heritage textile pattern with matching trim |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 swimsuit · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 헤드폰 · 헤드폰을 두 손으로 귀에 누른다 | presses over-ear headphones to her ears with both hands |

옷 종류 dress + robe · 옷 색 — · 옷 자유 · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 턱시도 재킷 + 캐미솔 + 정장 바지 | a sharp tuxedo jacket over a silk camisole with tailored trousers |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jacket + tank + trousers · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 잔·컵 · 잔을 입에 댄다 | brings a cup to her lips |

옷 종류 robe · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 detail

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 옆모습 | kneeling on the ground |
| 손 · 소품 동작 | prop · prop · 책 · 책을 읽는다 | reads a book held open in both hands |

옷 종류 swimsuit · 옷 색 — · 장면 자유(자유 장면) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place
