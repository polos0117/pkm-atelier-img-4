# 메더 (0618 · Stunfisk) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 4ac0589 · 2026-11-01T23:10:03.370Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 618 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 466 | `d2632b47354d` | `메더_light_glossy_promo_f.webp` |
| ② | heavy | ① 메더_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `77678f74be2d` | `메더_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 메더_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `21abcb0c2aa3` | `메더_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 메더_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `4045f2ee76e2` | `메더_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 메더_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `303d6e8eac40` | `메더_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 메더_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `b856b333624b` | `메더_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 메더_light_glossy_promo_f.webp | `casual1-prompt.txt` | 768 | `ede0e622c880` | `메더_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 메더_light_glossy_promo_f.webp | `casual2-prompt.txt` | 692 | `1507725efa4c` | `메더_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 메더_light_glossy_promo_f.webp | `casual3-prompt.txt` | 602 | `647e6d50168e` | `메더_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 traditional · 드러내기 cropped hem, high thigh slit · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 해변 | a sunny beach with wet sand and shallow surf |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 선글라스 · 접은 선글라스를 든다 | holds folded a pair of sunglasses by one arm |

옷 종류 traditional · 드러내기 off-shoulder neckline, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + skirt · 드러내기 high-cut leg, plunging neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
