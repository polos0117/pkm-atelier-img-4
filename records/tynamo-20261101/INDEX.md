# 저리어 (0602 · Tynamo) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 8a98025 · 2026-11-01T11:49:08.241Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 602 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 410 | `3241ef37aed4` | `저리어_light_glossy_promo_f.webp` |
| ② | heavy | ① 저리어_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `55fcd9e0a10d` | `저리어_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 저리어_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `92168982bc2a` | `저리어_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 저리어_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `d290bd1e963c` | `저리어_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 저리어_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `8b1d1c28bf2d` | `저리어_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 저리어_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `537dce105714` | `저리어_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 저리어_light_glossy_promo_f.webp | `casual1-prompt.txt` | 792 | `b70ae2d83b1d` | `저리어_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 저리어_light_glossy_promo_f.webp | `casual2-prompt.txt` | 668 | `de2c6ca8822c` | `저리어_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 저리어_light_glossy_promo_f.webp | `casual3-prompt.txt` | 666 | `447a99b7e8b5` | `저리어_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 옥상 | a city rooftop with a water tank, string lights and the skyline |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 승무원풍 | a retro flight-attendant-inspired costume with a fitted jacket, scarf and original airline-style trim |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 선글라스 · 선글라스를 손가락으로 내린다 | lowers a pair of sunglasses down her nose with one finger |

옷 종류 jacket · 드러내기 halter neck, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 댄스 무대 | a lit dance stage or milonga floor |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 해골 | a skeleton costume — a black stretch catsuit printed with white bones, worn with a red-rose flower crown |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 bodysuit · 드러내기 strapless top, mini length · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 선글라스 · 접은 선글라스를 든다 | holds folded a pair of sunglasses by one arm |

옷 종류 bodysuit + leggings · 드러내기 halter neck, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
