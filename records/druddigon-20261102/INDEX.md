# 크리만 (0621 · Druddigon) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 1d41ca2 · 2026-11-02T00:22:17.390Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 621 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 479 | `6c8a17b8281f` | `크리만_light_glossy_promo_f.webp` |
| ② | heavy | ① 크리만_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `c10f19721111` | `크리만_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 크리만_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `cce5f4b7cc91` | `크리만_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 크리만_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `bd6670eb04c4` | `크리만_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 크리만_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `2c2ef96e0748` | `크리만_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 크리만_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `af67fc7abaad` | `크리만_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 크리만_light_glossy_promo_f.webp | `casual1-prompt.txt` | 788 | `21feecc5018d` | `크리만_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 크리만_light_glossy_promo_f.webp | `casual2-prompt.txt` | 640 | `4dd2d5601161` | `크리만_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 크리만_light_glossy_promo_f.webp | `casual3-prompt.txt` | 748 | `82b0f97a775d` | `크리만_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 온천 마을 족욕 | a hot-spring town footbath under a wooden roof |
| 역할 | — |  |
| 의상 | 서브컬처 · 스케이터 | skater — a cropped hoodie, low-slung cargo shorts and high socks |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 수건 · 수건을 안는다 | holds a towel folded against her chest |

옷 종류 shorts + sweater · 드러내기 mini length, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 dress · 드러내기 high thigh slit, mini length · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 레트로 퓨처 집 | a retro-futurist home of rounded chrome appliances and soft panels |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 trousers · 드러내기 side cutouts, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit
