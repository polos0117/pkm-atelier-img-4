# 딱구리 (0076 · Golem) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 52a3ae5 · 2026-11-11T03:49:13.525Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 76 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 893 | `44a29ccf6ecb` | `딱구리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1165 | `014273923b3a` | `딱구리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1100 | `7134d47f5e50` | `딱구리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1192 | `3850aef7c978` | `딱구리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1166 | `df7e710ade57` | `딱구리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1020 | `3c872706e08c` | `딱구리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 995 | `3e47e0e2b303` | `딱구리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1191 | `a96411b22020` | `딱구리_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1120 | `236d746adea7` | `딱구리_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 딱구리_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1052 | `4984bec39355` | `딱구리_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 모험가 · 보물 사냥꾼 | a treasure-hunter look — a fitted tank top, a leather strap harness with small pouches, slim cargo pants and fingerless gloves |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 tank + trousers · 옷 색 — · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 란제리풍 · 자동 — 계열 안에서 장면에 맞게 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | strap · out |  |

옷 종류 slip · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, backless · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 직업복 · 케어 유니폼 | an original pastel care uniform — a fitted tunic dress with a short white apron |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 apron + dress + uniform · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | pet_companion · floor_brace |  |

옷 종류 cardigan + leggings · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 반쯤 푼 차림 · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 scene

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 밤 천문대 | a night observatory under an open dome |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | wave · down |  |

옷 종류 dress · 옷 색 — · 드러내기 plunging neckline, backless · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 해적 | a pirate costume — a laced black corset over an off-shoulder white blouse, a ragged mini skirt, thigh-high boots and a tricorn hat |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | hip · hair_tuck |  |

옷 종류 blouse + lingerie_set + skirt · 옷 색 — · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 물품점 | a wooden travel-supply shop counter with route maps and feed pouches |
| 역할 | — |  |
| 의상 | 전통 의상 · 유카타 | a light cotton summer yukata wrapped left over right with a soft obi and geta sandals |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 traditional · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bikini · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 하맘 | a domed marble hammam with warm stone slabs and brass bowls |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 카지노 딜러 | a casino dealer costume with a fitted waistcoat, bow tie and cuffs |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 vest · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 detail
