# 기기기어르 (0601 · Klinklang) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5d6bf5b · 2026-11-01T09:39:05.247Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 601 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 402 | `2d654890cdbc` | `기기기어르_light_glossy_promo_f.webp` |
| ② | heavy | ① 기기기어르_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `f93ad9272696` | `기기기어르_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 기기기어르_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `3247e5ca3341` | `기기기어르_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 기기기어르_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `bbe289aaee33` | `기기기어르_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 기기기어르_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `705007b9c18d` | `기기기어르_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 기기기어르_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `d6296c8bc2ba` | `기기기어르_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 기기기어르_light_glossy_promo_f.webp | `casual1-prompt.txt` | 737 | `e42fd95ca87e` | `기기기어르_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 기기기어르_light_glossy_promo_f.webp | `casual2-prompt.txt` | 757 | `7a5ab3323ea1` | `기기기어르_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 기기기어르_light_glossy_promo_f.webp | `casual3-prompt.txt` | 757 | `bb9d7739b02a` | `기기기어르_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 불꽃 막대 · 불꽃 막대를 들어 올린다 | holds a lit sparkler up beside her face |

옷 종류 tank · 드러내기 off-shoulder neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 전통 의상 · 유카타 | a light cotton summer yukata wrapped left over right with a soft obi and geta sandals |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 traditional · 드러내기 high thigh slit, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 장터 | a market street of a Pokémon-world town with awnings and baskets of goods |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 아이스크림 · 아이스크림을 든다 | holds an ice cream cone at chest height |

옷 종류 traditional · 드러내기 cropped hem, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit
