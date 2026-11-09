# 성원숭 (0057 · Primeape) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 31a3839 · 2026-11-09T16:06:29.025Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 57 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 878 | `2f6c4e93c9c4` | `성원숭_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1123 | `bdf23fac8fc9` | `성원숭_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1142 | `488dc4f5c7bb` | `성원숭_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1017 | `2da131da6a7d` | `성원숭_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1132 | `839fc2a992c2` | `성원숭_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1028 | `a000ef7e78a7` | `성원숭_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 996 | `66cb7d7270db` | `성원숭_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1056 | `2b92486cf567` | `성원숭_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1096 | `d37384468beb` | `성원숭_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 성원숭_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1099 | `8e4690900322` | `성원숭_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 몬스터볼 · 몬스터볼을 천으로 닦는다 | polishes a Poké Ball with a soft cloth |

옷 종류 traditional · 옷 색 코랄 · 오렌지 (coral and soft orange) · 상황 바람에 날림 · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 요트 갑판 | the cushioned foredeck of a moored yacht |
| 역할 | — |  |
| 의상 | 홈웨어 · 자동 — 계열 안에서 장면에 맞게 | soft homewear or loungewear |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 shorts + sweater · 옷 색 — · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 light · 직접 입력 outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 수영복 | a 1950s high-waisted pin-up swimsuit |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 수건 · 목에 건 수건 끝을 잡는다 | holds one end of a towel hung around her neck |

옷 종류 swimsuit · 옷 색 — · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 skirt + vest · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 달빛 연못 | a moonlit lotus pond with stepping stones and glowing fireflies |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 수영복 · 홀터 비키니 | a halter bikini with a neck tie and an underbust band |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 3/4 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 벽에 기대 서기 · waist_up · 옆모습 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 서식 공간 설계실 | a habitat design studio with shelter scale models and nest materials on a large table |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + shirt · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 모험가 · 사막 탐험가 | a desert-explorer look — a light linen scarf loose over the shoulders, a cropped linen top, low-slung loose linen trousers and leather sandals |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 trousers · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 detail
