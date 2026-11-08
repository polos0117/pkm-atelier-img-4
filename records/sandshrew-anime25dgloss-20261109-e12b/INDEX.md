# 모래두지 (0027 · Sandshrew) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 d338021 · 2026-11-08T21:52:06.051Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 27 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 868 | `5c2b9afbe040` | `모래두지_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1080 | `c624449ec33e` | `모래두지_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1108 | `0eba86f3f073` | `모래두지_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1129 | `ca051be9292d` | `모래두지_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 993 | `5714d25c1fbc` | `모래두지_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1114 | `cca0e1308740` | `모래두지_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1046 | `01c2022b0de0` | `모래두지_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1112 | `eb572dd7a6e1` | `모래두지_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1059 | `68bcb5da6887` | `모래두지_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 모래두지_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 970 | `f216a2b527cf` | `모래두지_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 목장 | a sunlit Pokémon ranch shelter with fresh straw and feed bins |
| 역할 | — |  |
| 의상 | 동탄룩 · 페스티벌 — 바디체인 + 크롭 + 데님 숏츠 | a music-festival outfit — a crochet crop top with a delicate body chain, frayed denim micro shorts and ankle boots |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 crop_top + shorts · 옷 색 스카이 · 네이비 (sky blue and navy) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 해적선 갑판 | the deck of a tall wooden sailing ship at sea — rigging, a ship's wheel, coiled ropes, wooden stairs up to the quarterdeck and billowing sails |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 해적 선장 | a pirate captain party costume — a cropped brocade coat over a cinched waist, a tricorn hat and tall boots |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 coat · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 웨딩 · 자동 — 계열 안에서 장면에 맞게 | bridal wear |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · face_close · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 폭포 웅덩이 | a rocky waterfall pool under green trees |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 dress · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 캠프장 | a quiet campsite with a small tent and a cooking kit |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 아라비안 나이트 | an Arabian-nights look — a jewelled cropped top, a sheer veil scarf over the shoulders, low-slung flowing chiffon trousers and gold coin anklets |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 불꽃 막대 · 불꽃 막대를 들어 올린다 | holds a lit sparkler up beside her face |

옷 종류 crop_top + trousers · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 걷기 · chest_up · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 인어 쇼 | a mermaid show costume — a scale-sequined bodice and a flowing chiffon wrap skirt |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 skirt · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 레트로 다이너 | a retro American diner — a chrome counter, vinyl booths, a jukebox and neon signs in the window |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · waist_up · 옆모습 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 댄스 무대 | a lit dance stage or milonga floor |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 슬립 | a bias-cut satin slip with narrow straps and a straight hem |
| 몸 자세 · 구도 | 서기 · full_body · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action
