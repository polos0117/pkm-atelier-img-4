# 슈륙챙이 (0061 · Poliwhirl) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5605c25 · 2026-11-09T23:49:08.764Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 61 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 841 | `3a1607639fe2` | `슈륙챙이_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1131 | `487f97b94861` | `슈륙챙이_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1092 | `0347b5a9db87` | `슈륙챙이_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1178 | `8a8d427c0a10` | `슈륙챙이_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1037 | `c47eacef96a9` | `슈륙챙이_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1121 | `1224323a3844` | `슈륙챙이_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1072 | `30a87608ed2b` | `슈륙챙이_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1126 | `241b4c308437` | `슈륙챙이_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 990 | `e22c888acf49` | `슈륙챙이_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 슈륙챙이_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1006 | `f9d6d0c25dfb` | `슈륙챙이_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 연습장 | an outdoor battle practice field marked with cones and chalk lines |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 bikini · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 공원 산책길 | a park path lined with trees and benches |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | pet_companion · floor_brace |  |

옷 종류 jacket + trousers · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 동탄룩 · 클럽 — 메탈릭 슬립 미니 | a club outfit — a liquid-metallic cowl-neck slip mini dress with thin straps and strappy heels |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 dress + slip · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 거대한 서고 | a vast fantasy library of towering shelves, spiral stairs and floating candles |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 전통 의상 · 부부 | a flowing West African boubou — a wide floor-length embroidered robe with a matching head wrap |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 robe · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 apron + shirt · 옷 색 라벤더 · 플럼 (lavender and plum) · 상황 반쯤 푼 차림 · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 트레이너 숙소 휴게실 | a trainers' lodge lounge at night with a fireplace, a small bar counter and wooden tables |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 인어 쇼 | a mermaid show costume — a scale-sequined bodice and a flowing chiffon wrap skirt |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 skirt · 옷 색 — · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 걷기 · full_body · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 detail
