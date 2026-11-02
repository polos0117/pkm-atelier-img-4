# 활화르바 (0636 · Larvesta) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 d1a9ff2 · 2026-11-02T14:26:20.601Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 636 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 394 | `e79a16c0e6ac` | `활화르바_light_glossy_promo_f.webp` |
| ② | heavy | ① 활화르바_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `1bb4f9811888` | `활화르바_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 활화르바_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `5686c2735705` | `활화르바_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 활화르바_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `f565d5894526` | `활화르바_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 활화르바_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `bcce02c9cbc6` | `활화르바_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 활화르바_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `fd71837cf651` | `활화르바_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 활화르바_light_glossy_promo_f.webp | `casual1-prompt.txt` | 681 | `e4c36ef26db2` | `활화르바_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 활화르바_light_glossy_promo_f.webp | `casual2-prompt.txt` | 611 | `0e02b01a4373` | `활화르바_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 활화르바_light_glossy_promo_f.webp | `casual3-prompt.txt` | 795 | `eda005c8e4b5` | `활화르바_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 비키니 | a 1950s pin-up bikini with a high-waisted bottom and a halter top |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · three_quarter · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 드러내기 halter neck, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 걷기 · environmental · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 드러내기 one-shoulder cut, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · face_close · 옆모습 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 coat + dress · 드러내기 high thigh slit, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
