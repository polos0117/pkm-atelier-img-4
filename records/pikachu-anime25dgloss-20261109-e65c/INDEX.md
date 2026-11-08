# 피카츄 (0025 · Pikachu) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 95e23f8 · 2026-11-08T16:48:09.084Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 25 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 885 | `45430202cff3` | `피카츄_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 피카츄_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1134 | `3a57a0a5b441` | `피카츄_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 피카츄_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 994 | `fc8ddc62ec5f` | `피카츄_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 피카츄_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1023 | `bbd3537e435a` | `피카츄_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 피카츄_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1108 | `1e07a1438600` | `피카츄_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 피카츄_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 976 | `9129a8a1fbd3` | `피카츄_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 피카츄_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1064 | `1a276d49adb7` | `피카츄_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 피카츄_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1076 | `20c7b25f2e6d` | `피카츄_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 blouse · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · full_body · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 란제리풍 · 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 숲길 | a forest trail junction with a wooden marker |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 바닥에 앉기 · face_close · 정면 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe + slip · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 걷기 · environmental · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 체육관·복싱장 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 무릎 꿇기 · chest_up · 3/4 정면 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 폭포 웅덩이 | a rocky waterfall pool under green trees |
| 역할 | — |  |
| 의상 | 레트로 · 60년대 리비에라 수영복 | a 1960s jet-set one-piece swimsuit with a headscarf and cat-eye sunglasses |
| 몸 자세 · 구도 | 물에 몸 담그기 · waist_up · 뒤 3/4 | chest-deep in the water |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 light
