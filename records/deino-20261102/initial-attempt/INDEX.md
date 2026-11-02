# 모노두 (0633 · Deino) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 41cb94b · 2026-11-02T13:08:43.124Z

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
| ⑧ | casual2 | ① 모노두_light_glossy_promo_f.webp | `casual2-prompt.txt` | 805 | `3fc2c387f9a0` | `모노두_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 모노두_light_glossy_promo_f.webp | `casual3-prompt.txt` | 628 | `90804a35daf7` | `모노두_glossy_promo_f_casual3.webp` |

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
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 apron + shirt · 드러내기 bare midriff, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 드러내기 mini length, one-shoulder cut · 장면 칸 첫머리 light · 직접 입력 scene, outfit
