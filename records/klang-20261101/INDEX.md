# 기기어르 (0600 · Klang) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 b722bbd · 2026-11-01T09:29:14.172Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 600 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 390 | `1dff300aed9f` | `기기어르_light_glossy_promo_f.webp` |
| ② | heavy | ① 기기어르_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `a4c1dd5b4a78` | `기기어르_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 기기어르_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `fc527e461c35` | `기기어르_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 기기어르_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `611953fe3943` | `기기어르_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 기기어르_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `8cd6dff610ed` | `기기어르_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 기기어르_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `b75c9397e9cf` | `기기어르_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 기기어르_light_glossy_promo_f.webp | `casual1-prompt.txt` | 739 | `23f92d8ad40f` | `기기어르_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 기기어르_light_glossy_promo_f.webp | `casual2-prompt.txt` | 753 | `b378154156e6` | `기기어르_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 기기어르_light_glossy_promo_f.webp | `casual3-prompt.txt` | 832 | `ebe77122cdb8` | `기기어르_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 skirt · 드러내기 off-shoulder neckline, cropped hem · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 수영복 · 반두 비키니 | a bandeau bikini with a straight strapless top |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 bikini + crop_top · 드러내기 high-cut leg, bare midriff · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 직업복 · 글래머 오피스룩 | glamorous tailored workwear — a fitted vest over a silk blouse and a high-waisted pencil skirt |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 국자 · 국자로 카레를 젓는다 | stirs a pot of berry curry with a ladle |

옷 종류 blouse + skirt + vest · 드러내기 off-shoulder neckline, cropped hem · 장면 칸 첫머리 place · 직접 입력 scene, outfit
