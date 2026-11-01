# 맘복치 (0594 · Alomomola) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 cabd969 · 2026-11-01T04:35:40.505Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 594 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 402 | `be8fff10bc5d` | `맘복치_light_glossy_promo_f.webp` |
| ② | heavy | ① 맘복치_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `d131f153c8fe` | `맘복치_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 맘복치_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `754418420bdf` | `맘복치_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 맘복치_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `831b094a5d09` | `맘복치_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 맘복치_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `0b6b7d9b5af1` | `맘복치_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 맘복치_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `79846c59f316` | `맘복치_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 맘복치_light_glossy_promo_f.webp | `casual1-prompt.txt` | 763 | `c9ad39aa87d7` | `맘복치_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 맘복치_light_glossy_promo_f.webp | `casual2-prompt.txt` | 796 | `476afcfea018` | `맘복치_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 맘복치_light_glossy_promo_f.webp | `casual3-prompt.txt` | 746 | `dca8d4016153` | `맘복치_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 침실 | her bedroom, an unmade bed and soft window light |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 기대 눕기 · chest_up · 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 coat + dress · 드러내기 mini length, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 숲길 조사지 | a forest trail edge with a marked trail post, used for wild Pokémon field surveys |
| 역할 | 탐사 지도 제작자 | an expedition cartographer |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 놋쇠 나침반 · 나침반을 평평히 들고 방향을 본다 | holds a brass compass level to check the way |

옷 종류 traditional · 드러내기 one-shoulder cut, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 공원 산책길 | a park path lined with trees and benches |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 jumpsuit · 드러내기 strapless top, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit
