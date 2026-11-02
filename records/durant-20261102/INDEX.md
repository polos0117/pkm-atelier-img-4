# 아이앤트 (0632 · Durant) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 41cb94b · 2026-11-02T13:08:43.001Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 632 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 438 | `1586757a9dc5` | `아이앤트_light_glossy_promo_f.webp` |
| ② | heavy | ① 아이앤트_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `dc03b1fd6a4e` | `아이앤트_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 아이앤트_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `1253843e4df4` | `아이앤트_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 아이앤트_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `62526b0345f4` | `아이앤트_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 아이앤트_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `8b53bc4ad51c` | `아이앤트_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 아이앤트_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `432cab3b962f` | `아이앤트_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 아이앤트_light_glossy_promo_f.webp | `casual1-prompt.txt` | 647 | `f9fdd8635c6f` | `아이앤트_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 아이앤트_light_glossy_promo_f.webp | `casual2-prompt.txt` | 662 | `b52a765faf65` | `아이앤트_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 아이앤트_light_glossy_promo_f.webp | `casual3-prompt.txt` | 792 | `9742c8e574d1` | `아이앤트_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 crop_top + skirt · 드러내기 bare midriff, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 uniform · 드러내기 mini length, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 하맘 | a domed marble hammam with warm stone slabs and brass bowls |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 trousers · 드러내기 halter neck, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit
