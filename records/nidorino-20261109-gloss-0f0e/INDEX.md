# 니드리노 (0033 · Nidorino) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 841a81a · 2026-11-09T07:08:13.764Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 33 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 878 | `9856bcba84e6` | `니드리노_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1154 | `b14e7711f525` | `니드리노_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1090 | `b21d44224750` | `니드리노_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1154 | `2afef53ef745` | `니드리노_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1084 | `1201140f4a6b` | `니드리노_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1103 | `b733e64325ba` | `니드리노_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1109 | `2cf4e1fb714d` | `니드리노_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1031 | `6c99eb3e82a8` | `니드리노_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1069 | `129ca146534a` | `니드리노_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 니드리노_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 990 | `483f3bbdb693` | `니드리노_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬센터 로비 | the bright lobby of a Pokémon Center with a reception counter, sofas and potted plants |
| 역할 | — |  |
| 의상 | 동탄룩 · 클럽 — 메탈릭 슬립 미니 | a club outfit — a liquid-metallic cowl-neck slip mini dress with thin straps and strappy heels |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 dress + slip · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 시장 | a busy street market of food stalls and strung bulbs |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 tank · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 직업복 · 연구복 | a white lab coat over a fitted knit top and slim trousers |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | wave · down |  |

옷 종류 coat + knit_top + trousers · 옷 색 아이보리 · 크림 (ivory and warm cream) · 상황 바람에 날림 · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 대회 무대 | a contest or tournament stage under spotlights |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 모험가 · 해적 코르셋 | a pirate look — a loose shirt open at the neck under a laced leather corset, a long sash at the hip, short breeches and tall cuffed boots |
| 몸 자세 · 구도 | 바닥에 앉기 · full_body · 뒤 3/4 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + shirt · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 숲길 | a forest trail junction with a wooden marker |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 — · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · waist_up · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 해적 | a pirate costume — a laced black corset over an off-shoulder white blouse, a ragged mini skirt, thigh-high boots and a tricorn hat |
| 몸 자세 · 구도 | 서기 · environmental · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + lingerie_set + skirt · 옷 색 — · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit
