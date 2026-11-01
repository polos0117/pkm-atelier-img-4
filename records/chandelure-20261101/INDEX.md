# 샹델라 (0609 · Chandelure) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 f07f388 · 2026-11-01T14:10:27.972Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 609 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 416 | `9d89295331d1` | `샹델라_light_glossy_promo_f.webp` |
| ② | heavy | ① 샹델라_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `9bcdaddccdb0` | `샹델라_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 샹델라_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `37cc52f110ed` | `샹델라_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 샹델라_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `22f68a4665c4` | `샹델라_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 샹델라_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `8f6f463ace53` | `샹델라_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 샹델라_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `1c1f1625710f` | `샹델라_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 샹델라_light_glossy_promo_f.webp | `casual1-prompt.txt` | 668 | `0c49140b7cce` | `샹델라_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 샹델라_light_glossy_promo_f.webp | `casual2-prompt.txt` | 744 | `5301112c73db` | `샹델라_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 샹델라_light_glossy_promo_f.webp | `casual3-prompt.txt` | 804 | `a97938f62159` | `샹델라_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 골목 | a narrow city alley with hanging signboards and wet pavement |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 롤러 디스코 | 1970s satin hot pants and a tube top |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 trousers · 드러내기 bare midriff, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 기차 침대칸 | a night-train sleeper compartment with a narrow berth, a fold-down table and a small window |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 dress · 드러내기 high thigh slit, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 수영장 | an outdoor pool with lounge chairs and clear blue water |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 챙 넓은 모자 · 쓴 모자 챙을 잡는다 | holds the brim of a wide-brimmed sun hat she wears |

옷 종류 uniform · 드러내기 open back, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit
