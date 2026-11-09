# 고라파덕 (0054 · Psyduck) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 28f1c59 · 2026-11-09T15:13:02.111Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 54 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 852 | `a961331d20b8` | `고라파덕_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1143 | `b07b8ddef589` | `고라파덕_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1047 | `892f6e3245e4` | `고라파덕_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1177 | `20e402bbe471` | `고라파덕_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1111 | `7898d206cdf5` | `고라파덕_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1117 | `2835a03b8f50` | `고라파덕_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1132 | `9c6920091b84` | `고라파덕_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1099 | `e364d0738d92` | `고라파덕_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1075 | `a61c4161e940` | `고라파덕_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 고라파덕_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1140 | `09b8567c6bcc` | `고라파덕_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 평상복 · 롱코트 + 머플러 | a long wool coat and a knitted scarf |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 접부채 · 부채로 얼굴을 가린다 | lifts a folding fan open to just below her eyes |

옷 종류 coat · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 | a city rooftop with a water tank, string lights and the skyline |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 기타 · 기타를 친다 | plays an acoustic guitar |

옷 종류 uniform · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 마을 | a small town square of the Pokémon world with a fountain, flower beds and tiled roofs |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 robe + slip · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 바람에 날림 · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 동탄룩 · 크롭 니트 + 타이트 미니스커트 | a tight cropped knit top baring the waist and a snug bodycon mini skirt, with high heels |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 knit_top + skirt · 옷 색 — · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 action · 직접 입력 scene

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 bikini · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 연구소 | a regional Pokémon research laboratory with a long desk, habitat maps on a board and field kits on shelves |
| 역할 | — |  |
| 의상 | 란제리풍 · 코르셋풍 | a corset-inspired bodice with visible boning seams and a matching high-waisted piece |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 lingerie_set · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 패션쇼장 | the front row of a fashion show beside a lit runway |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 캠프장 | a quiet campsite with a small tent and a cooking kit |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse · 옷 색 — · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit
