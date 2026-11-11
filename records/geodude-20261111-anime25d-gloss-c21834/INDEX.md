# 꼬마돌 (0074 · Geodude) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 cd55104 · 2026-11-11T01:57:09.326Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 74 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 876 | `b4c478b9d02a` | `꼬마돌_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1078 | `90dc51fb7cd7` | `꼬마돌_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1053 | `1f823f15f045` | `꼬마돌_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1131 | `5cd5fbcccbe6` | `꼬마돌_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1120 | `32133cbd2a3e` | `꼬마돌_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1013 | `1daa67579c53` | `꼬마돌_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1138 | `7480d5c908c7` | `꼬마돌_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1065 | `212fd6b037b4` | `꼬마돌_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1123 | `eb16f55f0ddf` | `꼬마돌_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 꼬마돌_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1084 | `1fa8e65a27e7` | `꼬마돌_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 온천 | an outdoor hot spring of a Pokémon-world mountain town, steam over smooth rocks |
| 역할 | — |  |
| 의상 | 란제리풍 · 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 slip · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 하맘 | a domed marble hammam with warm stone slabs and brass bowls |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 짧은 페플로스 | a short draped peplos mini dress belted with a fine gold chain, laurel-leaf hair pins and laced gladiator sandals |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · full_body · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 바람에 날림 · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 장구 아틀리에 | an equipment atelier with saddle pads, travel harnesses and design samples on display |
| 역할 | — |  |
| 의상 | 평상복 · 니트 + 레깅스 | a chunky knit sweater and leggings |
| 몸 자세 · 구도 | 걷기 · environmental · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 leggings + sweater · 옷 색 — · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 서브컬처 · 로맨틱 고스 | romantic goth — a black velvet dress with a corset belt and lace sleeves |
| 몸 자세 · 구도 | 엎드리기 · face_close · 정면 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress + lingerie_set · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 롤러장 | a roller rink under coloured lights |
| 역할 | — |  |
| 의상 | 수영복 · 홀터 비키니 | a halter bikini with a neck tie and an underbust band |
| 몸 자세 · 구도 | 엎드리기 · environmental · 뒤 3/4 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 온실·식물원 | a glass greenhouse full of plants with a wooden potting bench |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 옷 색 — · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · full_body · 뒤 3/4 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 직업복 · 자동 — 계열 안에서 장면에 맞게 | practical clothing for her Pokémon-world job, readable through its tools |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls + tank · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공연장 대기실 | a backstage dressing room with a bulb-lit mirror, a vanity table and costume racks |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, open back · 장면 칸 첫머리 action
