# 라플레시아 (0045 · Vileplume) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 87e324d · 2026-11-09T13:30:36.556Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 45 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 867 | `badd9e423553` | `라플레시아_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1076 | `3f0c697f2fe9` | `라플레시아_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1082 | `fd46b5f13de7` | `라플레시아_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1024 | `6a1f8aa9965e` | `라플레시아_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1149 | `f3ecec88755b` | `라플레시아_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1029 | `d8d8ed5bdb60` | `라플레시아_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1109 | `cf9a46814162` | `라플레시아_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1172 | `87c88190031d` | `라플레시아_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1188 | `4ad628a81e55` | `라플레시아_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 라플레시아_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1028 | `b181b7afed59` | `라플레시아_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 댄스 무대 | a lit dance stage or milonga floor |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 traditional · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 대리석 신전 | a sunlit white marble temple — tall fluted columns and a terrace above a deep blue sea |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 검은 고양이 | a black cat costume — a glossy black strapless bodysuit, sheer black tights, a cat-ear headband, a curling tail and a bell choker |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 detail · 직접 입력 outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 tank · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 마을 지붕 테라스 | a rooftop terrace above a Pokémon-world harbor town |
| 역할 | — |  |
| 의상 | 직업복 · 학예사 카디건 | a neat cardigan over slim trousers with white cotton gloves |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 cardigan + trousers · 옷 색 — · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 침실 | her bedroom, an unmade bed and soft window light |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 옆모습 | crouching low on her heels |
| 손 · 소품 동작 | prop · natural · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 bikini · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 레트로 다이너 | a retro American diner — a chrome counter, vinyl booths, a jukebox and neon signs in the window |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | prop · prop · 편지 · 편지를 두 손으로 읽는다 | reads a handwritten letter held in both hands |

옷 종류 uniform · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 밤 택시 | the back seat of a taxi at night, city lights streaking past |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 서기 · waist_up · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress + robe · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, backless · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 아라비안 나이트 | an Arabian-nights look — a jewelled cropped top, a sheer veil scarf over the shoulders, low-slung flowing chiffon trousers and gold coin anklets |
| 몸 자세 · 구도 | 서기 · three_quarter · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + trousers · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 action
