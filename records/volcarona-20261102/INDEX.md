# 불카모스 (0637 · Volcarona) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 d1a9ff2 · 2026-11-02T14:26:20.746Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 637 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 416 | `2b89f02f3d62` | `불카모스_light_glossy_promo_f.webp` |
| ② | heavy | ① 불카모스_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `1fb07fe0d15c` | `불카모스_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 불카모스_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `b3292adcfa04` | `불카모스_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 불카모스_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `6b76eec9a544` | `불카모스_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 불카모스_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `e73dce8f6073` | `불카모스_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 불카모스_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `ebb6c4ea0b07` | `불카모스_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 불카모스_light_glossy_promo_f.webp | `casual1-prompt.txt` | 695 | `558a3f815e3f` | `불카모스_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 불카모스_light_glossy_promo_f.webp | `casual2-prompt.txt` | 698 | `5633ca1b0213` | `불카모스_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 불카모스_light_glossy_promo_f.webp | `casual3-prompt.txt` | 688 | `0c83af3d8e4c` | `불카모스_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 카메라 · 사진을 찍는다 | raises a camera to her eye to take a photo |

옷 종류 traditional · 드러내기 high thigh slit, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 런웨이 | a fashion runway under white spotlights |
| 역할 | — |  |
| 의상 | 레트로 · 90년대 미니멀 슬립 | a 1990s minimal satin slip dress under a small cropped cardigan |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 옆모습 | sitting on the ground |
| 손 · 소품 동작 | lap · floor_brace |  |

옷 종류 cardigan + dress + slip · 드러내기 one-shoulder cut, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 crop_top + skirt · 드러내기 mini length, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit
