# 니드런♀ (0029 · Nidoran♀) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 0ae6693 · 2026-11-09T01:15:33.981Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다(우리 옷 계열에 없는 것 위주로).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 29 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 888 | `0caadcbf826f` | `니드런♀_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1109 | `03f12e718bad` | `니드런♀_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1114 | `e22f42563182` | `니드런♀_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1167 | `1cf22a060855` | `니드런♀_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1116 | `55e56e8b671e` | `니드런♀_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1051 | `c97a4834d8e3` | `니드런♀_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1006 | `0c4b6b19babe` | `니드런♀_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1093 | `f444eeba2f16` | `니드런♀_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1027 | `43d090484ec1` | `니드런♀_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 니드런♀_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1010 | `586c05b67cc6` | `니드런♀_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 평상복 · 선드레스 + 가디건 | a sundress with a light cardigan |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 cardigan + dress · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 shirt · 옷 색 — · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 swimsuit · 옷 색 민트 · 틸 (mint and teal) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 리그 경기장 | a Pokémon League arena with a reception desk, a marked battle court and a commentary desk |
| 역할 | — |  |
| 의상 | 모험가 · 보물 사냥꾼 | a treasure-hunter look — a fitted tank top, a leather strap harness with small pouches, slim cargo pants and fingerless gloves |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 옆모습 | kneeling on the ground |
| 손 · 소품 동작 | prop · prop · 노트와 펜 · 노트에 쓴다 | writes in a notebook with a pen on the table |

옷 종류 tank + trousers · 옷 색 — · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온천 마을 족욕 | a hot-spring town footbath under a wooden roof |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 슬립 | a bias-cut satin slip with narrow straps and a straight hem |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 slip · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 동탄룩 · 페스티벌 — 바디체인 + 크롭 + 데님 숏츠 | a music-festival outfit — a crochet crop top with a delicate body chain, frayed denim micro shorts and ankle boots |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | pet_companion · floor_brace |  |

옷 종류 crop_top + shorts · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 패션쇼장 | the front row of a fashion show beside a lit runway |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · environmental · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 구름 위 정자 | an open pavilion floating above a sea of clouds at sunrise |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 detail
