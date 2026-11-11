# 데구리 (0075 · Graveler) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 a797816 · 2026-11-11T02:35:10.338Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 75 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 883 | `c1734def2210` | `데구리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 데구리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1172 | `be9fcf1567e1` | `데구리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 데구리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1075 | `f78197d8aa91` | `데구리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 데구리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1122 | `674473dbd7d0` | `데구리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 데구리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1084 | `a3d5ef923f3c` | `데구리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 데구리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1009 | `2b533e975eda` | `데구리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 데구리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1173 | `9fbfefbfef5d` | `데구리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 데구리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1043 | `4287ae36b507` | `데구리_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 데구리_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1024 | `b3a265a34d35` | `데구리_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 데구리_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1184 | `b8ede3e7b644` | `데구리_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 dress + slip · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 마을 지붕 테라스 | a rooftop terrace above a Pokémon-world harbor town |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 blouse + traditional · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온천 마을 족욕 | a hot-spring town footbath under a wooden roof |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 skirt + sweater · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 직업복 · 사육 작업복 | work overalls over a fitted tank top and rubber boots |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 overalls + tank · 옷 색 — · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 수영복 · 부르키니 | a modest full-cover swimsuit with long sleeves, full legs and a fitted hood |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 3/4 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 바닥에 앉기 · waist_up · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress + robe · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 별빛 무대 | a stage under a painted night sky of crystal stars |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 로데오 카우걸 | a rodeo cowgirl costume — a fringed cropped vest, a western hat, short denim and cowboy boots |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 vest · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 육상 트랙 | a running track with lane lines and a grandstand |
| 역할 | — |  |
| 의상 | 동탄룩 · 크롭 니트 + 타이트 미니스커트 | a tight cropped knit top baring the waist and a snug bodycon mini skirt, with high heels |
| 몸 자세 · 구도 | 옆으로 눕기 · waist_up · 정면 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 knit_top + skirt · 옷 색 세이지 · 올리브 (sage and olive green) · 상황 바람에 날림 · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 place
