# 리그레 (0605 · Elgyem) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 1bc63d1 · 2026-11-01T13:03:37.929Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 605 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 415 | `fbe09912b7e5` | `리그레_light_glossy_promo_f.webp` |
| ② | heavy | ① 리그레_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `899c2d9cb899` | `리그레_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 리그레_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `e5e6c286e923` | `리그레_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 리그레_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `87c5fe8fb2a3` | `리그레_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 리그레_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `435be64cf09a` | `리그레_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 리그레_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `42c7d1fdb6cb` | `리그레_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 리그레_light_glossy_promo_f.webp | `casual1-prompt.txt` | 656 | `2d72be040b1b` | `리그레_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 리그레_light_glossy_promo_f.webp | `casual2-prompt.txt` | 747 | `69f0e9effe8e` | `리그레_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 리그레_light_glossy_promo_f.webp | `casual3-prompt.txt` | 728 | `28511ef0e168` | `리그레_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 쇼핑백 · 쇼핑백을 든다 | carries a paper shopping bag at her side |

옷 종류 lingerie_set + skirt · 드러내기 bare midriff, strapless top · 장면 칸 첫머리 place

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 요트 갑판 | the cushioned foredeck of a moored yacht |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 드레스 | a thin-strapped satin slip dress that flows along the body |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 dress + slip · 드러내기 high thigh slit, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 리그 경기장 | a Pokémon League arena with a reception desk, a marked battle court and a commentary desk |
| 역할 | — |  |
| 의상 | 란제리풍 · 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 slip · 드러내기 high thigh slit, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
