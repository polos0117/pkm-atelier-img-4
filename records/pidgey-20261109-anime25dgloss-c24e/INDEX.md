# 구구 (0016 · Pidgey) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 48b7874 · 2026-11-08T17:46:06.849Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 16 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 882 | `e27f155b9b35` | `구구_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 구구_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1076 | `d4196a03834c` | `구구_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 구구_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1048 | `12b3b9551ccc` | `구구_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 구구_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1018 | `d1cd2009ae6e` | `구구_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 구구_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1096 | `178919f65254` | `구구_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 구구_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1084 | `ef17a567e06c` | `구구_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 구구_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1118 | `0447d3cba7ec` | `구구_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 구구_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1060 | `4013ac01c58a` | `구구_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 jumpsuit · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 레트로 퓨처 집 | a retro-futurist home of rounded chrome appliances and soft panels |
| 역할 | — |  |
| 의상 | 수영복 · 딥 플런지 원피스 | a one-piece swimsuit with a deep plunging V and a secure wide waistband |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 | a covered porch on a rainy day, umbrellas resting by the door |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 걷기 · full_body · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · waist_up · 뒤 3/4 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 place · 직접 입력 scene

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 양궁장 | an archery range of targets on a green field |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 걷기 · waist_up · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 볼룸 가운 | a flowing ballroom gown with a fitted bodice |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene, outfit
