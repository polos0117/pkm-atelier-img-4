# 뿔충이 (0013 · Weedle) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 2aa37bb · 2026-11-08T17:37:48.879Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 13 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 840 | `f1f29a577dc6` | `뿔충이_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1203 | `9f380606203d` | `뿔충이_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1118 | `037d95a00dd5` | `뿔충이_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1030 | `271abab7403c` | `뿔충이_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1166 | `047969058050` | `뿔충이_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1130 | `211f880359c5` | `뿔충이_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1020 | `880920bdb6bb` | `뿔충이_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 뿔충이_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1073 | `2120c7588763` | `뿔충이_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 엘프 | an elf costume — a leaf-trimmed short dress, a hooded half-cape and pointed ear tips |
| 몸 자세 · 구도 | 쪼그려 앉기 · waist_up · 뒤 3/4 | crouching low on her heels |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 coat + dress · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 skirt + vest · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 벽에 기대 서기 · full_body · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + traditional · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 겨울 산장 테라스 | a snowy mountain-lodge terrace with a wooden railing and benches above a winter valley |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 서기 · waist_up · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · full_body · 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 테마 행사장 | a themed costume event venue with props and a photo wall |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 걷기 · chest_up · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene
