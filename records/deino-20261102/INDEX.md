# 모노두 (0633 · Deino) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 41cb94b · 2026-11-02T13:37:03.355Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 633 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 429 | `86b2e455ed6c` | `모노두_light_glossy_promo_f.webp` |
| ② | heavy | ① 모노두_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `c5bbc9b17826` | `모노두_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 모노두_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `ec5738e732ff` | `모노두_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 모노두_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `7b08e51ff87e` | `모노두_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 모노두_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `95b599fb084f` | `모노두_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 모노두_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `8a40a3fc5fd4` | `모노두_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 모노두_light_glossy_promo_f.webp | `casual1-prompt.txt` | 661 | `bce0f8ec1cfb` | `모노두_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 모노두_light_glossy_promo_f.webp | `casual2-prompt.txt` | 687 | `19f160037cb9` | `모노두_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 모노두_light_glossy_promo_f.webp | `casual3-prompt.txt` | 783 | `8221834eb2c6` | `모노두_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · three_quarter · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 드러내기 high thigh slit, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 시장 | a busy street market of food stalls and strung bulbs |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 dress · 드러내기 high thigh slit, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 턱시도 재킷 + 캐미솔 + 정장 바지 | a sharp tuxedo jacket over a silk camisole with tailored trousers |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 jacket + tank + trousers · 드러내기 bare midriff, halter neck · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
