# 뚜벅쵸 (0043 · Oddish) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bab0bad · 2026-11-08T23:02:09.823Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 43 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 821 | `8a12f6e19b6c` | `뚜벅쵸_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1149 | `9b488960e235` | `뚜벅쵸_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 981 | `a9c0bbd29fee` | `뚜벅쵸_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1046 | `5a095108cdd1` | `뚜벅쵸_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1147 | `5d9c9fa306bd` | `뚜벅쵸_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1128 | `f181071fe78d` | `뚜벅쵸_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 994 | `f1080dfad7fb` | `뚜벅쵸_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 973 | `a037c03e0df4` | `뚜벅쵸_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1038 | `9a87fb60e79c` | `뚜벅쵸_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 뚜벅쵸_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 976 | `7cc91d0de5be` | `뚜벅쵸_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 | a village market stall piled with fresh berries |
| 역할 | — |  |
| 의상 | 평상복 · 터틀넥 + 퀼팅 조끼 + 바지 | a fine knit turtleneck under a quilted vest with straight trousers |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 trousers + vest · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 홈웨어 · 플리스 상의 + 조거 팬츠 | a soft fleece pullover with relaxed jogger pants |
| 몸 자세 · 구도 | 엎드리기 · full_body · 옆모습 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 sweater + trousers · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · chest_up · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 동반 호텔 | the reception counter of a Pokémon-friendly hotel |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · face_close · 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 서브컬처 · 이모 | emo — a fitted striped long-sleeve top, a studded belt, skinny jeans and checkered sneakers |
| 몸 자세 · 구도 | 의자에 앉기 · waist_up · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 trousers · 옷 색 블랙 · 차콜 (black with charcoal accents) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 케이블카 | a cable car cabin over a misty valley |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 뒤 3/4 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 불꽃놀이 강변 | a riverside seating area waiting for festival fireworks |
| 역할 | — |  |
| 의상 | 웨딩 · 자동 — 계열 안에서 장면에 맞게 | bridal wear |
| 몸 자세 · 구도 | 서기 · environmental · 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 무릎 꿇기 · full_body · 뒤 3/4 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 걷기 · three_quarter · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 light
