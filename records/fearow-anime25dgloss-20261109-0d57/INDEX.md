# 깨비드릴조 (0022 · Fearow) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bab0bad · 2026-11-08T23:32:19.656Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 22 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 860 | `092ad2626d2e` | `깨비드릴조_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1135 | `4230532055f5` | `깨비드릴조_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1099 | `c3a6ff3085c5` | `깨비드릴조_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1100 | `3bbe3883aa69` | `깨비드릴조_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 968 | `7776ca29d883` | `깨비드릴조_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1037 | `3f8bb279e748` | `깨비드릴조_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1058 | `ed8ef3aabd9b` | `깨비드릴조_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1039 | `7f3c4c115a8d` | `깨비드릴조_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1071 | `723a000773e8` | `깨비드릴조_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 깨비드릴조_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 999 | `a4835f0bc34e` | `깨비드릴조_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 shorts + sweater · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 swimsuit · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | — |  |
| 의상 | 전통 의상 · 모로코 카프탄 | a Moroccan evening caftan — a long embroidered robe with a decorated belt |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 반쯤 푼 차림 · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 양궁장 | an archery range of targets on a green field |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 서기 · full_body · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shirt · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 히노키 탕 | a cedar-wood tub by the window of a mountain inn |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + traditional · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 기차 침대칸 | a night-train sleeper compartment with a narrow berth, a fold-down table and a small window |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 정비용 점프수트 | a fitted mechanic's work jumpsuit with rolled sleeves and no real logos |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 작은 가게 | a small shop — a bookstore, record store or plant shop — with crowded shelves |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 해변 | a sunny beach with wet sand and shallow surf |
| 역할 | — |  |
| 의상 | 동탄룩 · 크롭 니트 + 타이트 미니스커트 | a tight cropped knit top baring the waist and a snug bodycon mini skirt, with high heels |
| 몸 자세 · 구도 | 물에 몸 담그기 · waist_up · 옆모습 | chest-deep in the water |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + skirt · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 place
