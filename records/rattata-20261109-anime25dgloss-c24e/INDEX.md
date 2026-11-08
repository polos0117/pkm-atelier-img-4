# 꼬렛 (0019 · Rattata) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 48b7874 · 2026-11-08T17:46:07.143Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 19 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 852 | `091dac28999f` | `꼬렛_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 꼬렛_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1170 | `209b31e6de78` | `꼬렛_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 꼬렛_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1013 | `d6d04420751b` | `꼬렛_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 꼬렛_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1016 | `0588745321b0` | `꼬렛_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 꼬렛_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1076 | `41a495bded75` | `꼬렛_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 꼬렛_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 997 | `7dc68128784e` | `꼬렛_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 꼬렛_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1065 | `04817d8788a9` | `꼬렛_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 꼬렛_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1169 | `3e249eb669d7` | `꼬렛_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 보호구역 | a Pokémon reserve with habitat gates, shaded water bowls and spacious planted enclosures |
| 역할 | — |  |
| 의상 | 직업복 · 학예사 카디건 | a neat cardigan over slim trousers with white cotton gloves |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 cardigan + trousers · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 레트로 퓨처 집 | a retro-futurist home of rounded chrome appliances and soft panels |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · three_quarter · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 란제리풍 · 코튼 세트 | a simple cotton lingerie set with plain wide bands |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 수영장 | an outdoor pool with lounge chairs and clear blue water |
| 역할 | — |  |
| 의상 | 평상복 · 홀터 탑 + 짧은 반바지 | a halter top and short shorts |
| 몸 자세 · 구도 | 물에 몸 담그기 · waist_up · 정면 | chest-deep in the water |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shorts · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 옆으로 눕기 · three_quarter · 3/4 정면 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 overalls · 옷 색 — · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 양궁장 | an archery range of targets on a green field |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · full_body · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 vest · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 shorts · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit
