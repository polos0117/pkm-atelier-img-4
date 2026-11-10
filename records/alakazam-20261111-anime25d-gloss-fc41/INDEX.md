# 후딘 (0065 · Alakazam) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 cc8c3b5 · 2026-11-10T21:56:35.693Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 65 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 903 | `d43dcd306b9b` | `후딘_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 후딘_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1160 | `57a49a32d4c3` | `후딘_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 후딘_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1062 | `1b1883dc344d` | `후딘_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 후딘_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1151 | `5f64599c4a5d` | `후딘_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 후딘_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1142 | `70de13c9419c` | `후딘_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 후딘_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1130 | `84c41d72a1bd` | `후딘_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 후딘_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1167 | `db7a7730d38e` | `후딘_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 후딘_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1200 | `9bd81784bdb4` | `후딘_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 후딘_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1143 | `322f677aa202` | `후딘_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 후딘_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1044 | `e5accce5b447` | `후딘_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 거실 | her living room with a deep sofa, floor cushions and a low table |
| 역할 | — |  |
| 의상 | 서브컬처 · 로맨틱 고스 | romantic goth — a black velvet dress with a corset belt and lace sleeves |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 dress + lingerie_set · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 콘테스트장 | a Pokémon Contest hall with a decorated stage, ribbon displays and audience seats |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 슬립 | a bias-cut satin slip with narrow straps and a straight hem |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 옆모습 | sitting on the ground |
| 손 · 소품 동작 | lap · floor_brace |  |

옷 종류 slip · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 바니 코스튬 | a retro casino bunny costume with a fitted one-piece, cuffs, bow-tie collar and rabbit-ear headband |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 swimsuit · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 마녀 | a dark witch costume — a plunging black velvet bodysuit under a sheer black chiffon cape, a crooked wide-brimmed pointed hat and sheer thigh-high stockings |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 bodysuit + coat · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 수영복 · 트라이앵글 비키니 | a triangle bikini with slider cups and tie-side bottoms |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 bikini · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 정면 | lying on her side |
| 손 · 소품 동작 | behind_head · floor_brace |  |

옷 종류 robe + slip · 옷 색 — · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 댄스 무대 | a lit dance stage or milonga floor |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 카메라 · 사진을 찍는다 | raises a camera to her eye to take a photo |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 폭포 웅덩이 | a rocky waterfall pool under green trees |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 선글라스 · 선글라스를 손가락으로 내린다 | lowers a pair of sunglasses down her nose with one finger |

옷 종류 traditional · 옷 색 — · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 요정 숲 정원 | a misty enchanted garden of moss, ivy and lanterns |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | wave · down |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 light
