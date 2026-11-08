# 캐터피 (0010 · Caterpie) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 90de5b3 · 2026-11-08T16:50:55.710Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 10 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 855 | `ce34914104d4` | `캐터피_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1011 | `51b83047d025` | `캐터피_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1020 | `6fc4f4472576` | `캐터피_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1115 | `d8ecc56ad414` | `캐터피_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1095 | `3291cfe90885` | `캐터피_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1087 | `b257b7561b8a` | `캐터피_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1055 | `d171e4664b1e` | `캐터피_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1052 | `2b36f2659e83` | `캐터피_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 blouse + traditional · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 수영복 · 컷아웃 원피스 | a fully lined one-piece swimsuit with large cut-outs at the sides of the waist |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 swimsuit · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 서기 · environmental · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 직업복 · 학예사 카디건 | a neat cardigan over slim trousers with white cotton gloves |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 cardigan + trousers · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 목욕 차림 · 페슈테말 | a striped cotton peshtemal wrapped like a dress |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 옆모습 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 양궁장 | an archery range of targets on a green field |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + skirt · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 action
