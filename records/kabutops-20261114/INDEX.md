# 투구푸스 (0141 · Kabutops) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bb96270 · 2026-11-14T05:42:29.087Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 141 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 981 | `5f3f5dd79f3e` | `투구푸스_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1209 | `f50671f344ca` | `투구푸스_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1081 | `24c10dfd907a` | `투구푸스_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1160 | `359f1495d4e4` | `투구푸스_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1223 | `c6953abe676d` | `투구푸스_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1150 | `b34b146c11fe` | `투구푸스_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1068 | `b469c0983ec0` | `투구푸스_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1209 | `64a0200da4e6` | `투구푸스_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1110 | `3488f3a26d7d` | `투구푸스_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1116 | `bfdfab27ffda` | `투구푸스_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1216 | `d19fa164752d` | `투구푸스_anime_25d_gloss_f_casual10.webp` |
| ◆ | casual90 | ① 투구푸스_light_anime_25d_gloss_f.webp | `casual90-prompt.txt` | 1092 | `4ae02eba65ba` | `투구푸스_anime_25d_gloss_f_casual90.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 jacket + trousers · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 휴양지 차림 · 등 파인 선드레스 | a backless halter sundress with a short flared hem and espadrilles |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 dress · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 대리석 신전 | a sunlit white marble temple — tall fluted columns and a terrace above a deep blue sea |
| 역할 | — |  |
| 의상 | 란제리풍 · 자동 — 계열 안에서 장면에 맞게 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 slip · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 해골 | a skeleton costume — a black stretch catsuit printed with white bones, worn with a red-rose flower crown |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill |
| 손 · 소품 동작 | prop · rail · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bodysuit · 옷 색 — · 옷 자유 · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 동탄룩 · 크롭 니트 + 타이트 미니스커트 | a tight cropped knit top baring the waist and a snug bodycon mini skirt, with high heels |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 knit_top + skirt · 옷 색 — · 장면 자유(자유 장면) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공항 라운지 | an airport lounge — tall windows onto the runway, sleek seats, a long bench and a departures board |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 정면 | seated on a chair |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 바닥에 앉기 · waist_up · 뒤 3/4 | sitting on the ground |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 traditional · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 | a city rooftop with a water tank, string lights and the skyline |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 uniform · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코스프레 행사 | a convention photo zone under ring lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 의자에 앉기 · chest_up · 정면 | seated on a chair |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, open back · 장면 칸 첫머리 place

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 쪼그려 앉기 · environmental · 정면 | crouching low on her heels |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 robe + slip · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 바람에 날림 · 드러내기 deep V neckline, backless · 장면 칸 첫머리 detail

## ◆ casual90 — 캐릭터만의 컷(헬멧 피팅 장인 · 노출 bold)

일상 열 장에 더하는 한 장 — 채울 칸이 없다. 막히면 같은 지시문으로 두 번 더(모두 세 번), 그래도 막히면 계획기 `--own --own-level` 로 한 단계 내려 다시 짓는다(IMAGE_RULES 3절 「캐릭터만의 컷」).

| 칸 | 표의 글 |
|---|---|
| 장소 | a helmet shop — wall racks of helmets in many colors, a fitting stool, a glass counter with visors and straps |
| 장면 | she is a veteran fitter sitting sideways on the fitting stool, adjusting the strap of a helmet with both hands and a sharp eye |
| 의상 | a helmet fitter look fitted to her body — a fitted shop vest over a cropped tank top and short denim shorts, bare shoulders and legs, sneakers, a pair of small shears clipped at her hip |
| 도구 | a glossy full-face helmet (sig_both) |
| 자세 추천 | side_chair_read |
