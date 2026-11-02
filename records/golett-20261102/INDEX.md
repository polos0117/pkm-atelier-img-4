# 골비람 (0622 · Golett) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 6fa2278 · 2026-11-02T00:35:21.072Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 622 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 415 | `c62425a1c560` | `골비람_light_glossy_promo_f.webp` |
| ② | heavy | ① 골비람_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `acf7d186b3a0` | `골비람_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 골비람_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `8a7521b27646` | `골비람_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 골비람_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `14836ba71d33` | `골비람_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 골비람_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `b8bfa15036b7` | `골비람_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 골비람_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `54e52e286a6d` | `골비람_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 골비람_light_glossy_promo_f.webp | `casual1-prompt.txt` | 755 | `28d5e0f0c87e` | `골비람_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 골비람_light_glossy_promo_f.webp | `casual2-prompt.txt` | 685 | `be76646cade4` | `골비람_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 골비람_light_glossy_promo_f.webp | `casual3-prompt.txt` | 743 | `d890616e3c17` | `골비람_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bodysuit + leggings · 드러내기 bare midriff, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 미래풍 스파 | a futuristic spa of white curves and soft light |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 옆으로 눕기 · three_quarter · 정면 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 드러내기 one-shoulder cut, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 주방 | her home kitchen with a counter, open shelves and hanging pans |
| 역할 | — |  |
| 의상 | 직업복 · 연구복 | a white lab coat over a fitted knit top and slim trousers |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 coat + knit_top + trousers · 드러내기 cropped hem, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit
