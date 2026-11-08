# 어니부기 (0008 · Wartortle) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 90de5b3 · 2026-11-08T17:07:08.038Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 8 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 871 | `9a81b2fd401d` | `어니부기_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 어니부기_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1003 | `6e0271f56784` | `어니부기_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 어니부기_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1155 | `a5eab3a244af` | `어니부기_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 어니부기_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1116 | `dbfcaa129c55` | `어니부기_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 어니부기_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1066 | `cf6b0599b408` | `어니부기_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 어니부기_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1016 | `4925a4acce6c` | `어니부기_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 어니부기_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1052 | `f264bc2ca6fa` | `어니부기_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 어니부기_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 998 | `59bae0de0199` | `어니부기_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 시장 | a busy street market of food stalls and strung bulbs |
| 역할 | — |  |
| 의상 | 수영복 · 홀터 비키니 | a halter bikini with a neck tie and an underbust band |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | wave · down |  |

옷 종류 bikini · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 해적 선장 | a pirate captain party costume — a cropped brocade coat over a cinched waist, a tricorn hat and tall boots |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 coat · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 란제리풍 · 나이트 로브 + 란제리 | a lingerie set under an open silk night robe with a tied sash |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 lingerie_set + robe · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 홀터 플레이수트 | a 1950s halter playsuit |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 jumpsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 뒤 3/4 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 skirt · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 미라 | a mummy costume — a fitted bandage-wrap mini dress of layered cream gauze strips, bare shoulders and loose trailing wrap ends |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 3/4 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 place
