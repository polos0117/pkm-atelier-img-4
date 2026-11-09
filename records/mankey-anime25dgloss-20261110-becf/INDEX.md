# 망키 (0056 · Mankey) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 068ab50 · 2026-11-09T15:45:49.864Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 56 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 869 | `2ae716995f95` | `망키_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 망키_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1076 | `7f74f4dc393f` | `망키_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 망키_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1077 | `768228add53c` | `망키_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 망키_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1058 | `db4138baac4b` | `망키_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 망키_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1187 | `79efd9e3325d` | `망키_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 망키_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1114 | `a315607a85f3` | `망키_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 망키_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1177 | `f1676df6a530` | `망키_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 망키_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1118 | `5baab931bc23` | `망키_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 망키_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1031 | `cd9fd728f413` | `망키_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 망키_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1065 | `5f16f9dce71e` | `망키_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 쇼핑몰 | a shopping mall atrium with a fountain and glass railings |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · chest_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · face_close · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + overalls · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 직업복 · 글래머 오피스룩 | glamorous tailored workwear — a fitted vest over a silk blouse and a high-waisted pencil skirt |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + skirt + vest · 옷 색 레드 · 와인 (deep red and wine) · 상황 반쯤 푼 차림 · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 콘테스트 무대 뒤 | backstage of a Pokémon Contest hall with a rehearsal platform, prop racks and stage lights |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 의자에 앉기 · waist_up · 뒤 3/4 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + traditional · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 옷 색 — · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 가운 + 이브닝 코트 | a long gown under an evening coat |
| 몸 자세 · 구도 | 엎드리기 · full_body · 뒤 3/4 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 coat + dress · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 가면무도회장 | a chandelier ballroom at a masquerade |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 deep V neckline, open back · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 축제 거리 | a festival street of lanterns, food stalls and paper decorations |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 action
