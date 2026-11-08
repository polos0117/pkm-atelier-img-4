# 꼬부기 (0007 · Squirtle) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 96bb577 · 2026-11-08T16:34:32.492Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 7 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 883 | `c1700e971e01` | `꼬부기_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 꼬부기_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 988 | `d1d38ae3670a` | `꼬부기_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 꼬부기_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1080 | `0b1090a328b2` | `꼬부기_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 꼬부기_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1081 | `543763b76599` | `꼬부기_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 꼬부기_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 977 | `4e6d2f903e7f` | `꼬부기_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 꼬부기_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1084 | `188d14b1e596` | `꼬부기_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 꼬부기_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1061 | `c6e4f2270d39` | `꼬부기_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 꼬부기_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1111 | `827746fd77d7` | `꼬부기_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 야외 공연장 | an outdoor theatre of tiered seats facing a stage |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 traditional · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 란제리풍 · 나이트 로브 + 란제리 | a lingerie set under an open silk night robe with a tied sash |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + robe · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 로토무 제품 쇼룸 | a bright design showroom of household appliance prototypes |
| 역할 | — |  |
| 의상 | 직업복 · 안내원 재킷 | a neat guide jacket with a scarf over a blouse and a knee-length skirt |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 blouse + jacket + skirt · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 하맘 | a domed marble hammam with warm stone slabs and brass bowls |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 서기 · full_body · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 목욕 차림 · 수영복 위 가운 | a spa robe open over a swimsuit |
| 몸 자세 · 구도 | 쪼그려 앉기 · waist_up · 3/4 정면 | crouching low on her heels |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe + swimsuit · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 걷기 · face_close · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 place
