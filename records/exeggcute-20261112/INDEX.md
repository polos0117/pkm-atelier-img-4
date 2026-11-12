# 아라리 (0102 · Exeggcute) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 df4f754 · 2026-11-12T13:42:50.833Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 102 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 890 | `6845384d67d2` | `아라리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 아라리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1103 | `c55ae4358202` | `아라리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 아라리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 996 | `14f875c15a90` | `아라리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 아라리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1120 | `d5da23be47f1` | `아라리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 아라리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1144 | `47d8ed6758d3` | `아라리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 아라리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1086 | `aabb1e746cc8` | `아라리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 아라리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1112 | `59bb347d5748` | `아라리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 아라리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1038 | `5c34fe4c0474` | `아라리_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 아라리_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 989 | `a9efd9f68532` | `아라리_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 아라리_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1048 | `72f2d85e88ab` | `아라리_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 아라리_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1123 | `62702f25e2c1` | `아라리_anime_25d_gloss_f_casual10.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 축제 거리 | a festival street of lanterns, food stalls and paper decorations |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 jacket + trousers · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 홈웨어 · 오버사이즈 티 + 쇼츠 | an oversized tee and shorts |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shorts · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 옆모습 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron + shirt · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 장구 아틀리에 | an equipment atelier with saddle pads, travel harnesses and design samples on display |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · environmental · 뒤 3/4 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 골목 | a narrow city alley with hanging signboards and wet pavement |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + traditional · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 히노키 탕 | a cedar-wood tub by the window of a mountain inn |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 아라비안 나이트 | an Arabian-nights look — a jewelled cropped top, a sheer veil scarf over the shoulders, low-slung flowing chiffon trousers and gold coin anklets |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · waist_up · 뒤 3/4 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + trousers · 옷 색 — · 옷 자유 · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 대리석 목욕궁 | a Roman marble bath hall — columns, mosaic floors and a wide steaming pool lit from high windows |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 카지노 딜러 | a casino dealer costume with a fitted waistcoat, bow tie and cuffs |
| 몸 자세 · 구도 | 엎드리기 · full_body · 뒤 3/4 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 vest · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 시골 역 | a small rural station with a wooden bench and a single platform |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · three_quarter · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 마을 | a small town square of the Pokémon world with a fountain, flower beds and tiled roofs |
| 역할 | — |  |
| 의상 | 모험가 · 카우걸 | a cowgirl look — a cropped plaid shirt knotted under the bust, frayed denim shorts, a leather belt with a big buckle, cowboy boots and a cowboy hat |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shirt + shorts · 옷 색 — · 장면 자유(자유 장면) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 light

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 밤 택시 | the back seat of a taxi at night, city lights streaking past |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 의자에 앉기 · waist_up · 옆모습 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + overalls · 옷 색 스카이 · 네이비 (sky blue and navy) · 상황 흘러내린 어깨끈 · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 detail
