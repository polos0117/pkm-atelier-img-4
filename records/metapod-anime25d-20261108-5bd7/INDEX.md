# 단데기 (0011 · Metapod) — 지시문 묶음

화풍 `anime_25d` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 70bd656 · 2026-11-08T14:46:23.137Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 11 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 686 | `52c38bcfee50` | `단데기_light_anime_25d_f.webp` |
| ② | casual1 | ① 단데기_light_anime_25d_f.webp | `casual1-prompt.txt` | 892 | `2b2626a1caed` | `단데기_anime_25d_f_casual1.webp` |
| ③ | casual2 | ① 단데기_light_anime_25d_f.webp | `casual2-prompt.txt` | 969 | `88bc6987bca4` | `단데기_anime_25d_f_casual2.webp` |
| ④ | casual3 | ① 단데기_light_anime_25d_f.webp | `casual3-prompt.txt` | 1008 | `cb5dd57b628d` | `단데기_anime_25d_f_casual3.webp` |
| ⑤ | casual4 | ① 단데기_light_anime_25d_f.webp | `casual4-prompt.txt` | 945 | `bfdb5055cb0f` | `단데기_anime_25d_f_casual4.webp` |
| ⑥ | casual5 | ① 단데기_light_anime_25d_f.webp | `casual5-prompt.txt` | 957 | `a981bbe6eaec` | `단데기_anime_25d_f_casual5.webp` |
| ⑦ | casual6 | ① 단데기_light_anime_25d_f.webp | `casual6-prompt.txt` | 952 | `b4f71a4e7ac1` | `단데기_anime_25d_f_casual6.webp` |
| ⑧ | casual7 | ① 단데기_light_anime_25d_f.webp | `casual7-prompt.txt` | 958 | `ef8372a80bd4` | `단데기_anime_25d_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 뒤 3/4 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 jumpsuit · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 엎드리기 · face_close · 정면 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe + slip · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + shirt · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 카메라 · 찍은 사진을 확인한다 | checks the photo on the back screen of a camera at chest height |

옷 종류 uniform · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 수영복 · 부르키니 | a modest full-cover swimsuit with long sleeves, full legs and a fitted hood |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 light
