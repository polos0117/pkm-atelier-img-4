# 아쿠스타 (0121 · Starmie) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 86f0210 · 2026-11-13T12:46:18.400Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 121 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 906 | `56671e2b4b00` | `아쿠스타_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1190 | `2d277cf23638` | `아쿠스타_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1163 | `59bccf28a4a0` | `아쿠스타_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1105 | `c36021730489` | `아쿠스타_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1061 | `d134f1000625` | `아쿠스타_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1249 | `88041685edee` | `아쿠스타_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1169 | `f13220adf56d` | `아쿠스타_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1142 | `3d823d3176a4` | `아쿠스타_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1208 | `a499cea0a6f7` | `아쿠스타_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1206 | `a3dc85841f26` | `아쿠스타_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1150 | `c739a7e9cfed` | `아쿠스타_anime_25d_gloss_f_casual10.webp` |
| ◆ | casual90 | ① 아쿠스타_light_anime_25d_gloss_f.webp | `casual90-prompt.txt` | 1066 | `0a69d1808f0b` | `아쿠스타_anime_25d_gloss_f_casual90.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 정비 창고 | a maintenance shed with a long workbench, tool racks overhead and its door open onto the yard |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 휴양지 차림 · 등 파인 선드레스 | a backless halter sundress with a short flared hem and espadrilles |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 dress · 옷 색 — · 장면 자유(자유 장면) · 드러내기 deep V neckline, backless · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 얼음 궁전 | an ice palace hall of carved crystal pillars, frosted light and a grand frozen staircase |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 한 발 올려 서기 · full_body · 3/4 정면 | standing with one foot up on a step, the other leg straight |
| 손 · 소품 동작 | hip · natural |  |

옷 종류 tank · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 볕 드는 베란다 | a sunny enclosed veranda with drying racks overhead, floor cushions and a sliding glass door |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 bikini · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 lingerie_set · 옷 색 — · 옷 자유 · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 강변 자전거 길 | a riverside cycle path with a parked bicycle, a low stone wall and reeds along the water |
| 역할 | — |  |
| 의상 | 레트로 · 90년대 윈드브레이커 + 트랙 팬츠 | a color-blocked 1990s windbreaker with matching track pants |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 jacket + trousers · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 헌책 노점 | a second-hand book stall under an awning on a quiet street, crates of books on trestle tables and a folding stool |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 uniform · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 홈웨어 · 아침 로브 | a loosely tied robe |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 robe · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 서브컬처 · 록 | rock — a leather mini skirt, a cropped vest and a choker |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 skirt + vest · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 place

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 정거장 | a small station or dock platform of a Pokémon-world town, benches, a signal post and a waiting carriage |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 걷기 · environmental · 뒤 3/4 | walking |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 swimsuit · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 넥타이 · 스카프를 풀어 내림 · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action

## ◆ casual90 — 캐릭터만의 컷(등대장 · 노출 bold)

일상 열 장에 더하는 한 장 — 채울 칸이 없다. 막히면 같은 지시문으로 두 번 더(모두 세 번), 그래도 막히면 계획기 `--own --own-level` 로 한 단계 내려 다시 짓는다(IMAGE_RULES 3절 「캐릭터만의 컷」).

| 칸 | 표의 글 |
|---|---|
| 장소 | a seaside lighthouse — a white tower with a spiral stair, a railing, rocky shore and a starry sunset sea |
| 장면 | she is the keeper standing by the railing with her hands folded, gazing out at the starry sunset sea |
| 의상 | a lighthouse keeper look fitted to her body — a fitted sleeveless sailor top and short pleated skirt with deck shoes, bare shoulders and legs, a glowing gem-like brooch with a gold star |
| 도구 | — |
| 자세 추천 | clasp_low |
