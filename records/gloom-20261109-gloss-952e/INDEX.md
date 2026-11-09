# 냄새꼬 (0044 · Gloom) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 841a81a · 2026-11-09T06:34:11.950Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 44 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 867 | `4606a154a931` | `냄새꼬_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1109 | `98ab434118c8` | `냄새꼬_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1093 | `fb5d353d8480` | `냄새꼬_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1065 | `252d7360d779` | `냄새꼬_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1148 | `a4a38803a37f` | `냄새꼬_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1251 | `53e419e5efb7` | `냄새꼬_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1143 | `8cdf3b789dc0` | `냄새꼬_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1081 | `cc2129db14bd` | `냄새꼬_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 970 | `4e073db05cd1` | `냄새꼬_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 냄새꼬_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1058 | `2b902f2c3567` | `냄새꼬_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 거울 미궁 | a mirrored labyrinth of endless reflections and soft coloured light |
| 역할 | — |  |
| 의상 | 화보 쿠튀르 · 전통 구조 쿠튀르 | couture that keeps the structure and fastenings of a traditional dress |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 dress · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 traditional · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 란제리풍 · 보디수트 | a lingerie bodysuit with a scooped neckline, wide straps and lace side panels |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 bodysuit + lingerie_set · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 온천 | an outdoor hot spring of a Pokémon-world mountain town, steam over smooth rocks |
| 역할 | — |  |
| 의상 | 직업복 · 자동 — 계열 안에서 장면에 맞게 | practical clothing for her Pokémon-world job, readable through its tools |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 overalls + tank · 옷 색 — · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 목욕 차림 · 수영복 위 가운 | a spa robe open over a swimsuit |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 robe + swimsuit · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 바람에 날림 · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 action · 직접 입력 scene

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 공항 라운지 | an airport lounge — tall windows onto the runway, sleek seats, a long bench and a departures board |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 cardigan + leggings · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 야외 공연장 | an outdoor theatre of tiered seats facing a stage |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 로데오 카우걸 | a rodeo cowgirl costume — a fringed cropped vest, a western hat, short denim and cowboy boots |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 vest · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 place

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 옆모습 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 시스루 유령 | a sheer ghost costume — layers of translucent white chiffon draped over a short white satin slip |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 휴대용 게임기 · 휴대용 게임기로 논다 | plays on a handheld game console |

옷 종류 slip · 옷 색 — · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 light · 직접 입력 outfit
