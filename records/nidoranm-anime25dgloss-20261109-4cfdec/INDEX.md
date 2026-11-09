# 니드런♂ (0032 · Nidoran♂) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 522c992 · 2026-11-09T04:14:37.475Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 32 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 854 | `4756c6284532` | `니드런♂_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1077 | `1771cdbdaf37` | `니드런♂_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1083 | `fe9409d881d1` | `니드런♂_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1014 | `386362eef4d3` | `니드런♂_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1073 | `98cc1e0da124` | `니드런♂_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1090 | `7cfc0fd5de5d` | `니드런♂_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1151 | `ba92d29b0bfe` | `니드런♂_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 982 | `0184dcd1cd04` | `니드런♂_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1045 | `f761911f432e` | `니드런♂_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 니드런♂_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1149 | `b68f85011328` | `니드런♂_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 산장 | a mountain lodge with a front counter and a fireplace |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 cardigan + leggings · 옷 색 — · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 place · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 얼음 궁전 | an ice palace hall of carved crystal pillars, frosted light and a grand frozen staircase |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 dress · 옷 색 — · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 시스루 유령 | a sheer ghost costume — layers of translucent white chiffon draped over a short white satin slip |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 slip · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 정면 | lying on her side |
| 손 · 소품 동작 | behind_head · floor_brace |  |

옷 종류 swimsuit · 옷 색 — · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 uniform · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 shirt · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 수영복 · 홀터 비키니 | a halter bikini with a neck tie and an underbust band |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | hip · hair_tuck |  |

옷 종류 bikini · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 tank · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 | a covered porch on a rainy day, umbrellas resting by the door |
| 역할 | — |  |
| 의상 | 모험가 · 해적 코르셋 | a pirate look — a loose shirt open at the neck under a laced leather corset, a long sash at the hip, short breeches and tall cuffed boots |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | pet_companion · floor_brace |  |

옷 종류 lingerie_set + shirt · 옷 색 레드 · 와인 (deep red and wine) · 상황 반쯤 푼 차림 · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 detail · 직접 입력 scene
