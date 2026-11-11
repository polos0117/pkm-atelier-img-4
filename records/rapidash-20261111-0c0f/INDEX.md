# 날쌩마 (0078 · Rapidash) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 52a3ae5 · 2026-11-11T03:22:37.623Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 78 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 897 | `ae0666fb3cae` | `날쌩마_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1179 | `b4ae51c82c32` | `날쌩마_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 990 | `c30d0d279078` | `날쌩마_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1189 | `98e7dcb69619` | `날쌩마_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1117 | `9127bb2ffd5e` | `날쌩마_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1075 | `165938e42c0b` | `날쌩마_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1113 | `4ceb56247d2f` | `날쌩마_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1105 | `0994e1609f45` | `날쌩마_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 994 | `a8e82df4ce2a` | `날쌩마_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 날쌩마_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1047 | `df5834b7032c` | `날쌩마_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 인어 쇼 | a mermaid show costume — a scale-sequined bodice and a flowing chiffon wrap skirt |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | prop · prop · 나무열매 주스 주전자 · 주스를 잔에 따른다 | pours from a pitcher of berry juice into a glass |

옷 종류 skirt · 옷 색 — · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 수영복 · 랩 프론트 | a wrap-front swimsuit with a crossed bodice tied at the waist |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 모험가 · 비행사 | a vintage aviatrix look — a cropped leather flight jacket over a fitted top, high-waisted jodhpurs, goggles pushed up on her head and tall boots |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 jacket · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 밤 천문대 | a night observatory under an open dome |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · full_body · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 걷기 · waist_up · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 deep V neckline, backless · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 늑대 | a she-wolf costume — a grey faux-fur crop top and mini skirt, a wolf-ear headband, a fluffy tail and fingerless gloves |
| 몸 자세 · 구도 | 벽에 기대 서기 · face_close · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 체육관·복싱장 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 역할 | — |  |
| 의상 | 직업복 · 글래머 레인저룩 | a fitted ranger shirt knotted at the waist over high-waisted utility shorts and lace-up boots |
| 몸 자세 · 구도 | 걷기 · environmental · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shirt + shorts · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 바람에 날림 · 드러내기 plunging neckline, open back · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 란제리풍 · 벨벳 세트 | a deep-coloured velvet bralette and high-waisted bottoms |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 뒤 3/4 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 하맘 | a domed marble hammam with warm stone slabs and brass bowls |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 라이프가드 이벤트 | a lifeguard event costume — a red one-piece-style costume with a whistle on a cord |
| 몸 자세 · 구도 | 걷기 · full_body · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 detail
