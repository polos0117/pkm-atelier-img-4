# 이상해꽃 (0003 · Venusaur) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 2aa37bb · 2026-11-08T17:34:01.638Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 3 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 849 | `9432eea04465` | `이상해꽃_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 이상해꽃_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1148 | `935a0842d55c` | `이상해꽃_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 이상해꽃_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1158 | `d78cb999bf70` | `이상해꽃_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 이상해꽃_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1122 | `714d371d37ed` | `이상해꽃_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 이상해꽃_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1034 | `60d82d1df40f` | `이상해꽃_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 이상해꽃_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1070 | `0a9987f86b42` | `이상해꽃_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 이상해꽃_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1090 | `c20d7120fcbb` | `이상해꽃_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 이상해꽃_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1060 | `5bd9dff2065e` | `이상해꽃_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 traditional · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 직업복 · 연구복 | a white lab coat over a fitted knit top and slim trousers |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 동전 · 동전을 들어 보인다 | holds a single coin up between two fingers |

옷 종류 coat + knit_top + trousers · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 헤드폰 · 헤드폰을 두 손으로 귀에 누른다 | presses over-ear headphones to her ears with both hands |

옷 종류 robe · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 정비용 점프수트 | a fitted mechanic's work jumpsuit with rolled sleeves and no real logos |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 쇼핑백 · 쇼핑백을 든다 | carries a paper shopping bag at her side |

옷 종류 jumpsuit · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 요정 숲 정원 | a misty enchanted garden of moss, ivy and lanterns |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 dress · 옷 색 — · 드러내기 deep V neckline, open back · 장면 칸 첫머리 action · 직접 입력 scene

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 수영장 | an outdoor pool with lounge chairs and clear blue water |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 선글라스 · 접은 선글라스를 든다 | holds folded a pair of sunglasses by one arm |

옷 종류 shorts + tank · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 blouse + traditional · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
