# 거북왕 (0009 · Blastoise) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 2aa37bb · 2026-11-08T17:37:48.634Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 9 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 882 | `7e930007a376` | `거북왕_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 거북왕_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1161 | `0dca7ac71144` | `거북왕_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 거북왕_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1189 | `6246315c6080` | `거북왕_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 거북왕_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1121 | `62abda6702c6` | `거북왕_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 거북왕_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1122 | `da5269ab21f9` | `거북왕_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 거북왕_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1075 | `0852fd47a491` | `거북왕_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 거북왕_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1085 | `4aaca4a4f74f` | `거북왕_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 거북왕_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1017 | `fbb6957c4c2a` | `거북왕_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 가면 · 가면을 든다 | holds a masquerade mask on a stick up to her eyes |

옷 종류 crop_top + overalls · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야간 관측소 | a quiet hilltop observatory deck with a telescope under the night sky |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 턱시도 재킷 + 캐미솔 + 정장 바지 | a sharp tuxedo jacket over a silk camisole with tailored trousers |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 jacket + tank + trousers · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 카메라 · 사진을 찍는다 | raises a camera to her eye to take a photo |

옷 종류 uniform · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 나무열매 주스 주전자 · 주스를 잔에 따른다 | pours from a pitcher of berry juice into a glass |

옷 종류 shirt · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 온천 | an outdoor hot spring of a Pokémon-world mountain town, steam over smooth rocks |
| 역할 | — |  |
| 의상 | 수영복 · 컷아웃 원피스 | a fully lined one-piece swimsuit with large cut-outs at the sides of the waist |
| 몸 자세 · 구도 | 바닥에 앉기 · full_body · 정면 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 란제리풍 · 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |
| 몸 자세 · 구도 | 의자에 앉기 · waist_up · 뒤 3/4 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 테마 행사장 | a themed costume event venue with props and a photo wall |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 뒤 3/4 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 light · 직접 입력 scene
