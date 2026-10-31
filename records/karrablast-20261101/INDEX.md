# 딱정곤 (0588 · Karrablast) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 884227a · 2026-10-31T16:47:06.645Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 588 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 412 | `9845556fdcf3` | `딱정곤_light_glossy_promo_f.webp` |
| ② | heavy | ① 딱정곤_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `edfbbec45544` | `딱정곤_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 딱정곤_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `98b235e665eb` | `딱정곤_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 딱정곤_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `f0c9173aa9c0` | `딱정곤_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 딱정곤_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `ca2abc2c56b3` | `딱정곤_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 딱정곤_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `179679d0184b` | `딱정곤_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 딱정곤_light_glossy_promo_f.webp | `casual1-prompt.txt` | 716 | `82da2d24e74b` | `딱정곤_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 딱정곤_light_glossy_promo_f.webp | `casual2-prompt.txt` | 708 | `ae61cfd075d0` | `딱정곤_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 딱정곤_light_glossy_promo_f.webp | `casual3-prompt.txt` | 707 | `532f19d36c22` | `딱정곤_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 jacket + trousers · 드러내기 side cutouts, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 레트로 우주비행사 | a retro space-age costume — a fitted white jumpsuit with silver trim and moon boots |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 jumpsuit · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 레트로 퓨처 집 | a retro-futurist home of rounded chrome appliances and soft panels |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 홀터 플레이수트 | a 1950s halter playsuit |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | lap · natural |  |

옷 종류 jumpsuit · 드러내기 halter neck, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
