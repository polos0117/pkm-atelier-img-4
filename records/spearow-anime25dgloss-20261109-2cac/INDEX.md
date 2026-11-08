# 깨비참 (0021 · Spearow) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 80ab039 · 2026-11-08T21:17:50.130Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 21 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 858 | `95c468dac731` | `깨비참_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1076 | `7f6e5f0abb40` | `깨비참_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1126 | `d9a488b56958` | `깨비참_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1155 | `870c218eee49` | `깨비참_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1064 | `b126f2e110d5` | `깨비참_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1012 | `f1ec13a657e8` | `깨비참_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 991 | `4888eed3328e` | `깨비참_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1132 | `90fcafc1f913` | `깨비참_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 992 | `9f27976dc6e5` | `깨비참_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 깨비참_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1025 | `f442f6653356` | `깨비참_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 내 방 | her own room in a small house of a Pokémon-world town, a shelf of travel gear by the window |
| 역할 | — |  |
| 의상 | 모험가 · 비행사 | a vintage aviatrix look — a cropped leather flight jacket over a fitted top, high-waisted jodhpurs, goggles pushed up on her head and tall boots |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · environmental · 뒤 3/4 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jacket · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 리조트 카바나 | a resort cabana with a shaded daybed by the water |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 의자에 앉기 · waist_up · 뒤 3/4 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 대회 무대 | a contest or tournament stage under spotlights |
| 역할 | — |  |
| 의상 | 직업복 · 자동 — 계열 안에서 장면에 맞게 | practical clothing for her Pokémon-world job, readable through its tools |
| 몸 자세 · 구도 | 걷기 · chest_up · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 바람에 날림 · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 육상 트랙 | a running track with lane lines and a grandstand |
| 역할 | — |  |
| 의상 | 홈웨어 · 자동 — 계열 안에서 장면에 맞게 | soft homewear or loungewear |
| 몸 자세 · 구도 | 쪼그려 앉기 · waist_up · 뒤 3/4 | crouching low on her heels |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 전망대 | a hilltop lookout over a wide valley |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 자동 — 계열 안에서 장면에 맞게 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · three_quarter · 3/4 정면 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top · 옷 색 — · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 dress · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 란제리풍 · 자동 — 계열 안에서 장면에 맞게 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 몸 자세 · 구도 | 걷기 · full_body · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 action
