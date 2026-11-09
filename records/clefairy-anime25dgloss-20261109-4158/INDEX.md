# 삐삐 (0035 · Clefairy) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 1b9351b · 2026-11-09T03:30:35.856Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 35 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 857 | `1f1ada9b5220` | `삐삐_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1007 | `0060efa59e00` | `삐삐_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1019 | `6ff261a035ea` | `삐삐_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1114 | `07fd0fe73876` | `삐삐_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 968 | `d11ac35416b4` | `삐삐_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1119 | `6d1108f71c50` | `삐삐_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1055 | `f3fe262ac096` | `삐삐_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1108 | `7c856873f9ab` | `삐삐_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1116 | `e742338113c5` | `삐삐_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 삐삐_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1074 | `b6d92ad91089` | `삐삐_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 웨딩 · 자동 — 계열 안에서 장면에 맞게 | bridal wear |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 그레이 · 실버 (dove grey and silver) · 상황 바람에 날림 · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 하맘 | a domed marble hammam with warm stone slabs and brass bowls |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 레트로 우주비행사 | a retro space-age costume — a fitted white jumpsuit with silver trim and moon boots |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 뒤 3/4 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 의자에 앉기 · chest_up · 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 걷기 · three_quarter · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 육상 트랙 | a running track with lane lines and a grandstand |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 슬립 | a bias-cut satin slip with narrow straps and a straight hem |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 걷기 · chest_up · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 — · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 리조트 라군 데크 | a resort lagoon deck with stacked towels and lounge cushions |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 바닥에 앉기 · waist_up · 뒤 3/4 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 비키니 | a 1950s pin-up bikini with a high-waisted bottom and a halter top |
| 몸 자세 · 구도 | 서기 · full_body · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 place · 직접 입력 outfit
