# 나옹 (0052 · Meowth) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 841a81a · 2026-11-09T06:34:12.231Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 52 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 853 | `4d0a89113897` | `나옹_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 나옹_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1084 | `867b81c8491e` | `나옹_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 나옹_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 975 | `0132040e8ee3` | `나옹_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 나옹_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1051 | `d7087a2ce762` | `나옹_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 나옹_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1028 | `177002bf8a0b` | `나옹_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 나옹_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1093 | `96493b5510c6` | `나옹_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 나옹_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1096 | `7c1d373c0974` | `나옹_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 나옹_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 971 | `df655f77e337` | `나옹_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 나옹_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 975 | `74b19c32df3c` | `나옹_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 나옹_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1160 | `e550c2dc9a20` | `나옹_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 거울 미궁 | a mirrored labyrinth of endless reflections and soft coloured light |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 bikini · 옷 색 — · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 light · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 수영복 · 반두 비키니 | a bandeau bikini with a straight strapless top |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 bikini + crop_top · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 해적 선장 | a pirate captain party costume — a cropped brocade coat over a cinched waist, a tricorn hat and tall boots |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · environmental · 정면 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 coat · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 온천 | an outdoor hot spring of a Pokémon-world mountain town, steam over smooth rocks |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 엎드리기 · full_body · 뒤 3/4 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shirt · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 체육관·복싱장 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 역할 | — |  |
| 의상 | 평상복 · 얇은 블라우스 + 치마 | a thin blouse and a light skirt |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + skirt · 옷 색 아이보리 · 크림 (ivory and warm cream) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 웨딩 · 자동 — 계열 안에서 장면에 맞게 | bridal wear |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 — · 드러내기 deep V neckline, backless · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 야외 공연장 | an outdoor theatre of tiered seats facing a stage |
| 역할 | — |  |
| 의상 | 란제리풍 · 벨벳 세트 | a deep-coloured velvet bralette and high-waisted bottoms |
| 몸 자세 · 구도 | 무릎 꿇기 · full_body · 옆모습 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 인어 쇼 | a mermaid show costume — a scale-sequined bodice and a flowing chiffon wrap skirt |
| 몸 자세 · 구도 | 무릎 꿇기 · waist_up · 뒤 3/4 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 skirt · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene
