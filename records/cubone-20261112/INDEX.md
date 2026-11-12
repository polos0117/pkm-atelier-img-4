# 탕구리 (0104 · Cubone) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 df4f754 · 2026-11-12T14:00:26.110Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 104 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 891 | `e5e703c54f26` | `탕구리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1102 | `cee7dee2522e` | `탕구리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1131 | `51e6c9492406` | `탕구리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1231 | `558caf4c764c` | `탕구리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1100 | `0cf12649b12e` | `탕구리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1132 | `9a0d3d1d0d77` | `탕구리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1113 | `cbe38368ca81` | `탕구리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1152 | `adf31d6a8cd2` | `탕구리_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1056 | `922eb4eaeab7` | `탕구리_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1060 | `112d7976d9cc` | `탕구리_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 탕구리_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1072 | `dc08f21636a5` | `탕구리_anime_25d_gloss_f_casual10.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 나무열매 주스 주전자 · 주스를 잔에 따른다 | pours from a pitcher of berry juice into a glass |

옷 종류 robe + slip · 옷 색 — · 옷 자유 · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 폭포 웅덩이 | a rocky waterfall pool under green trees |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 상황 바람에 날림 · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 작은 가게 | a small shop — a bookstore, record store or plant shop — with crowded shelves |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 uniform · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 crop_top + jacket + trousers · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 해적 | a pirate costume — a laced black corset over an off-shoulder white blouse, a ragged mini skirt, thigh-high boots and a tricorn hat |
| 몸 자세 · 구도 | 걷기 · environmental · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + lingerie_set + skirt · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 옆으로 눕기 · face_close · 옆모습 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress + shirt · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 전통 의상 · 유카타 | a light cotton summer yukata wrapped left over right with a soft obi and geta sandals |
| 몸 자세 · 구도 | 서기 · full_body · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 옷 색 — · 장면 자유(자유 장면) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 서식 공간 설계실 | a habitat design studio with shelter scale models and nest materials on a large table |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · three_quarter · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 light

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 얼음 궁전 | an ice palace hall of carved crystal pillars, frosted light and a grand frozen staircase |
| 역할 | — |  |
| 의상 | 수영복 · 딥 플런지 원피스 | a one-piece swimsuit with a deep plunging V and a secure wide waistband |
| 몸 자세 · 구도 | 벽에 기대 서기 · full_body · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail
