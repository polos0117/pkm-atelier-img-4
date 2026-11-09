# 나인테일 (0038 · Ninetales) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 d2b2867 · 2026-11-09T12:26:40.375Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 38 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 865 | `6bc3f7600282` | `나인테일_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1084 | `b0931aec5a1a` | `나인테일_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1190 | `90b8cde316d7` | `나인테일_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1114 | `aaa69b3e3822` | `나인테일_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1049 | `c5001e5438c1` | `나인테일_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1139 | `c149baccb41b` | `나인테일_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1028 | `467bf3743b56` | `나인테일_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1070 | `ac92128a1b73` | `나인테일_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1089 | `5ba87d1ec652` | `나인테일_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 나인테일_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 988 | `d9333f79c931` | `나인테일_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 — · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 —

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야생 관찰 은신처 | a camouflaged field hide at the edge of a meadow, a tripod set inside |
| 역할 | — |  |
| 의상 | 홈웨어 · 플리스 상의 + 조거 팬츠 | a soft fleece pullover with relaxed jogger pants |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 sweater + trousers · 옷 색 — · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 공원 산책길 | a park path lined with trees and benches |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · full_body · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 — · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 —

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온천 마을 족욕 | a hot-spring town footbath under a wooden roof |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 걷기 · waist_up · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 — · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 —

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 서브컬처 · 록 | rock — a leather mini skirt, a cropped vest and a choker |
| 몸 자세 · 구도 | 걷기 · waist_up · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 — · 옷 색 그레이 · 실버 (dove grey and silver) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 plunging neckline, open back · 장면 칸 첫머리 —

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 란제리풍 · 코튼 세트 | a simple cotton lingerie set with plain wide bands |
| 몸 자세 · 구도 | 걷기 · environmental · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 — · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 —

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 모험가 · 자동 — 계열 안에서 장면에 맞게 | an adventurer's outfit — a rugged ranch, explorer or pirate look, practical pieces worn short and fitted |
| 몸 자세 · 구도 | 엎드리기 · environmental · 뒤 3/4 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 — · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 —

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 바닥에 앉기 · face_close · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 — · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 —
