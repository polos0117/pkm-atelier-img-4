# 리자드 (0005 · Charmeleon) — 지시문 묶음

화풍 `anime_25d` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 70bd656 · 2026-11-08T14:46:22.022Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 5 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 707 | `3c06fe5236a2` | `리자드_light_anime_25d_f.webp` |
| ② | casual1 | ① 리자드_light_anime_25d_f.webp | `casual1-prompt.txt` | 980 | `17c9e578467b` | `리자드_anime_25d_f_casual1.webp` |
| ③ | casual2 | ① 리자드_light_anime_25d_f.webp | `casual2-prompt.txt` | 1054 | `7e0c2bed698d` | `리자드_anime_25d_f_casual2.webp` |
| ④ | casual3 | ① 리자드_light_anime_25d_f.webp | `casual3-prompt.txt` | 1054 | `2efe7622622c` | `리자드_anime_25d_f_casual3.webp` |
| ⑤ | casual4 | ① 리자드_light_anime_25d_f.webp | `casual4-prompt.txt` | 859 | `472b1872e861` | `리자드_anime_25d_f_casual4.webp` |
| ⑥ | casual5 | ① 리자드_light_anime_25d_f.webp | `casual5-prompt.txt` | 989 | `af10b1ffb7e0` | `리자드_anime_25d_f_casual5.webp` |
| ⑦ | casual6 | ① 리자드_light_anime_25d_f.webp | `casual6-prompt.txt` | 928 | `a8f4eeec9883` | `리자드_anime_25d_f_casual6.webp` |
| ⑧ | casual7 | ① 리자드_light_anime_25d_f.webp | `casual7-prompt.txt` | 968 | `841259f04175` | `리자드_anime_25d_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 열차 객실 | a carriage of a Pokémon travel train with luggage racks and resting cushions |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 니트 | an off-shoulder knit top slipping from one shoulder over shorts |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · prop · 몬스터볼 · 몬스터볼을 천으로 닦는다 | polishes a Poké Ball with a soft cloth |

옷 종류 knit_top + shorts · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 내 방 | her own room in a small house of a Pokémon-world town, a shelf of travel gear by the window |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 기대 눕기 · chest_up · 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 수건 · 수건을 안는다 | holds a towel folded against her chest |

옷 종류 traditional · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 인어 쇼 | a mermaid show costume — a scale-sequined bodice and a flowing chiffon wrap skirt |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 skirt · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 걷기 · full_body · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 — · 드러내기 deep V neckline, open back · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 의전 교관 | a ceremonial instructor costume with a belted jacket, gloves and a decorative sash |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 수건 · 목에 건 수건 끝을 잡는다 | holds one end of a towel hung around her neck |

옷 종류 jacket · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 tank · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · chest_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 light
