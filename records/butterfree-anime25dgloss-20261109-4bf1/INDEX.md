# 버터플 (0012 · Butterfree) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 99f9fb0 · 2026-11-08T19:11:13.794Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 12 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 854 | `6284241a35a6` | `버터플_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 버터플_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1194 | `80370e1e472b` | `버터플_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 버터플_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1038 | `e54461fcfa3c` | `버터플_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 버터플_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1134 | `973053b95316` | `버터플_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 버터플_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1120 | `554d06b6db20` | `버터플_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 버터플_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1012 | `d87b0834ff24` | `버터플_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 버터플_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1150 | `ea524bd64561` | `버터플_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 버터플_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1031 | `b1ca1c343769` | `버터플_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 버터플_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1055 | `076eb4f16f87` | `버터플_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 버터플_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1112 | `8dbfcbbee5d6` | `버터플_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 동전 · 동전을 들어 보인다 | holds a single coin up between two fingers |

옷 종류 cardigan + leggings · 옷 색 민트 · 틸 (mint and teal) · 상황 흘러내린 어깨끈 · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 모험가 · 카우걸 | a cowgirl look — a cropped plaid shirt knotted under the bust, frayed denim shorts, a leather belt with a big buckle, cowboy boots and a cowboy hat |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 물병 · 물병을 든다 | holds a water bottle at chest height |

옷 종류 shirt + shorts · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 수영장 | an outdoor pool with lounge chairs and clear blue water |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 그리스 키톤 | a Greek chiton — a long draped dress pinned at both shoulders with gold brooches, a high side slit, a gold cord crossed under the bust and gold arm cuffs |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 튜브 · 튜브를 옆구리에 낀다 | carries a swim ring on one hip |

옷 종류 dress · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, backless · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 직업복 · 사육 작업복 | work overalls over a fitted tank top and rubber boots |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 overalls + tank · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 헤드폰 · 헤드폰을 두 손으로 귀에 누른다 | presses over-ear headphones to her ears with both hands |

옷 종류 robe · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 해적선 갑판 | the deck of a tall wooden sailing ship at sea — rigging, a ship's wheel, coiled ropes, wooden stairs up to the quarterdeck and billowing sails |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 정비용 점프수트 | a fitted mechanic's work jumpsuit with rolled sleeves and no real logos |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 jumpsuit · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 수영복 · 홀터 비키니 | a halter bikini with a neck tie and an underbust band |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 bikini · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 저녁 사무실 | a modern glass-walled office at dusk — a desk with a monitor, a swivel chair and city lights beyond the window |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 토트백 · 가방끈을 어깨에 걸쳐 잡는다 | holds the strap of a canvas tote bag on her shoulder |

옷 종류 blouse + traditional · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 place
