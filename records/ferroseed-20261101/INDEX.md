# 철시드 (0597 · Ferroseed) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 6810453 · 2026-11-01T05:13:04.352Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 597 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 405 | `ebc23bacf965` | `철시드_light_glossy_promo_f.webp` |
| ② | heavy | ① 철시드_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `e10f75e7acbc` | `철시드_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 철시드_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `7136a8e56f96` | `철시드_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 철시드_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 251 | `8309e7262e8c` | `철시드_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 철시드_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 257 | `12e08a40dce3` | `철시드_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 철시드_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 250 | `4e5032ca48bc` | `철시드_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 철시드_light_glossy_promo_f.webp | `casual1-prompt.txt` | 739 | `bcf39a3b58fb` | `철시드_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 철시드_light_glossy_promo_f.webp | `casual2-prompt.txt` | 689 | `59cb26f0bf32` | `철시드_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 철시드_light_glossy_promo_f.webp | `casual3-prompt.txt` | 766 | `f91583a0171c` | `철시드_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 동전 · 동전을 들어 보인다 | holds a single coin up between two fingers |

옷 종류 blouse + traditional · 드러내기 off-shoulder neckline, one-shoulder cut · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 서브컬처 · 스케이터 | skater — a cropped hoodie, low-slung cargo shorts and high socks |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 옆모습 | crouching low on her heels |
| 손 · 소품 동작 | prop · natural · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 shorts + sweater · 드러내기 mini length, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 traditional · 드러내기 high thigh slit, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
