# 야돈 (0079 · Slowpoke) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 e60e257 · 2026-11-11T13:17:00.121Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 79 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 907 | `30a0fa9bfb43` | `야돈_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 야돈_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1185 | `7744dc584397` | `야돈_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 야돈_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1146 | `ec00bf6a29bc` | `야돈_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 야돈_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1044 | `05ee82ec5a29` | `야돈_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 야돈_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1056 | `20b6b95dcaac` | `야돈_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 야돈_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1043 | `8c911d94c284` | `야돈_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 야돈_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1081 | `e4b7b1817765` | `야돈_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 야돈_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1051 | `7529bef1aa74` | `야돈_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 야돈_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1184 | `5e725bcef10a` | `야돈_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 야돈_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1229 | `73b7e217c05c` | `야돈_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 홈웨어 · 아침 로브 | a loosely tied robe |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 헤드폰 · 헤드폰을 두 손으로 귀에 누른다 | presses over-ear headphones to her ears with both hands |

옷 종류 robe · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 리조트 카바나 | a resort cabana with a shaded daybed by the water |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 아이스크림 · 아이스크림을 든다 | holds an ice cream cone at chest height |

옷 종류 robe + slip · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 물병 · 물병을 든다 | holds a water bottle at chest height |

옷 종류 traditional · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 야외 공연장 | an outdoor theatre of tiered seats facing a stage |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 uniform · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 시골 역 | a small rural station with a wooden bench and a single platform |
| 역할 | — |  |
| 의상 | 평상복 · 롱코트 + 머플러 | a long wool coat and a knitted scarf |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 coat · 옷 색 — · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 열차 객실 | a carriage of a Pokémon travel train with luggage racks and resting cushions |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 blouse + traditional · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 노트와 펜 · 노트에 쓴다 | writes in a notebook with a pen on the table |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · out |  |

옷 종류 swimsuit · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 목욕 차림 · 페슈테말 | a striped cotton peshtemal wrapped like a dress |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 dress · 옷 색 블랙 · 차콜 (black with charcoal accents) · 상황 흘러내린 어깨끈 · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene
