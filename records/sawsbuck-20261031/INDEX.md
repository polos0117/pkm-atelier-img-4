# 바라철록 (0586 · Sawsbuck) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 9c32bb3 · 2026-10-31T06:46:55.777Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 586 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 397 | `763f8a5adc01` | `바라철록_light_glossy_promo_f.webp` |
| ② | heavy | ① 바라철록_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `fdf636febcf3` | `바라철록_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 바라철록_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `c8c1a1fee51b` | `바라철록_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 바라철록_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `9624e6781cea` | `바라철록_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 바라철록_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `7329b2c2138a` | `바라철록_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 바라철록_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `8201d69541d8` | `바라철록_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 바라철록_light_glossy_promo_f.webp | `casual1-prompt.txt` | 775 | `b9bb284a926a` | `바라철록_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 바라철록_light_glossy_promo_f.webp | `casual2-prompt.txt` | 746 | `c4b16c04c433` | `바라철록_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 바라철록_light_glossy_promo_f.webp | `casual3-prompt.txt` | 732 | `936a81a32392` | `바라철록_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온실·식물원 | a glass greenhouse full of plants with a wooden potting bench |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 챙 넓은 모자 · 쓴 모자 챙을 잡는다 | holds the brim of a wide-brimmed sun hat she wears |

옷 종류 dress + slip · 드러내기 open back, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 traditional · 드러내기 cropped hem, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 직업복 · 글래머 앞치마 룩 | a sleek fitted wrap dress under a crisp short apron |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | wave · down |  |

옷 종류 apron + dress · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
