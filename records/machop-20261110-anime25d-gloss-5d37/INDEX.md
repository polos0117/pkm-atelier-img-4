# 알통몬 (0066 · Machop) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 9891b4f · 2026-11-10T04:04:09.923Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 66 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 906 | `ac41b4a955ab` | `알통몬_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1049 | `759a70d5e157` | `알통몬_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1092 | `2fc7efe6e8f0` | `알통몬_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1013 | `77231173b280` | `알통몬_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1127 | `924e09be6b19` | `알통몬_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 987 | `ee44f63ed40c` | `알통몬_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1172 | `3d8201dd5087` | `알통몬_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1073 | `8e7fe085a304` | `알통몬_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1017 | `1ef173154cb1` | `알통몬_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 알통몬_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1103 | `76984909f547` | `알통몬_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 인어 쇼 | a mermaid show costume — a scale-sequined bodice and a flowing chiffon wrap skirt |
| 몸 자세 · 구도 | 벽에 기대 서기 · full_body · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 skirt · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 모험가 · 비행사 | a vintage aviatrix look — a cropped leather flight jacket over a fitted top, high-waisted jodhpurs, goggles pushed up on her head and tall boots |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 jacket · 옷 색 라벤더 · 플럼 (lavender and plum) · 상황 흘러내린 어깨끈 · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 바닥에 앉기 · chest_up · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 옷 색 — · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 수영복 | a 1950s high-waisted pin-up swimsuit |
| 몸 자세 · 구도 | 서기 · three_quarter · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 — · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 로토무 제품 쇼룸 | a bright design showroom of household appliance prototypes |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | prop · prop · 몬스터볼 · 몬스터볼을 천으로 닦는다 | polishes a Poké Ball with a soft cloth |

옷 종류 traditional · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 밤 택시 | the back seat of a taxi at night, city lights streaking past |
| 역할 | — |  |
| 의상 | 란제리풍 · 자동 — 계열 안에서 장면에 맞게 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 몸 자세 · 구도 | 걷기 · chest_up · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 레트로 퓨처 집 | a retro-futurist home of rounded chrome appliances and soft panels |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · full_body · 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 겨울 산장 테라스 | a snowy mountain-lodge terrace with a wooden railing and benches above a winter valley |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 자동 — 계열 안에서 장면에 맞게 | a goddess-like draped look inspired by myth — flowing fabric wrapped, knotted and pinned on the body |
| 몸 자세 · 구도 | 걷기 · face_close · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 place
