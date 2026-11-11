# 포니타 (0077 · Ponyta) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 a797816 · 2026-11-11T02:35:10.546Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 77 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 882 | `e1108ec7618a` | `포니타_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 포니타_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1203 | `3ec1ec99d4bd` | `포니타_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 포니타_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1039 | `a2e5c40047cd` | `포니타_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 포니타_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1091 | `c06572ce82eb` | `포니타_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 포니타_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 999 | `68c5c0a90d1a` | `포니타_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 포니타_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1016 | `2abf73781242` | `포니타_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 포니타_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1162 | `4d4342f0c65b` | `포니타_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 포니타_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1121 | `6c0b6446ae56` | `포니타_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 포니타_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1103 | `ad1e5176a9bb` | `포니타_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 포니타_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1176 | `38ada08a9db9` | `포니타_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 엎드리기 · waist_up · 뒤 3/4 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 레드 · 와인 (deep red and wine) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 마을 지붕 테라스 | a rooftop terrace above a Pokémon-world harbor town |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 기대 눕기 · full_body · 뒤 3/4 | reclining on her back |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 수영장 | an outdoor pool with lounge chairs and clear blue water |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 옆으로 눕기 · environmental · 뒤 3/4 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 마녀 | a dark witch costume — a plunging black velvet bodysuit under a sheer black chiffon cape, a crooked wide-brimmed pointed hat and sheer thigh-high stockings |
| 몸 자세 · 구도 | 걷기 · full_body · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + coat · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 공항 라운지 | an airport lounge — tall windows onto the runway, sleek seats, a long bench and a departures board |
| 역할 | — |  |
| 의상 | 전통 의상 · 아오자이 | a Vietnamese áo dài — a long close-fitting silk tunic with a high mandarin collar over loose trousers |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 trousers · 옷 색 — · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 대리석 신전 | a sunlit white marble temple — tall fluted columns and a terrace above a deep blue sea |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · chest_up · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + shirt · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 레트로 다이너 | a retro American diner — a chrome counter, vinyl booths, a jukebox and neon signs in the window |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 의자에 앉기 · chest_up · 옆모습 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 안내소 | a Pokémon travel center with a visitor desk, route maps and lodging brochures |
| 역할 | — |  |
| 의상 | 모험가 · 보물 사냥꾼 | a treasure-hunter look — a fitted tank top, a leather strap harness with small pouches, slim cargo pants and fingerless gloves |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 tank + trousers · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 detail
