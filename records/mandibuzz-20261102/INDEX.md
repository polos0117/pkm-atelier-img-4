# 버랜지나 (0630 · Mandibuzz) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7ac5e2d · 2026-11-02T12:14:59.318Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 630 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 409 | `977f54645fce` | `버랜지나_light_glossy_promo_f.webp` |
| ② | heavy | ① 버랜지나_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `cc4a5b7fd378` | `버랜지나_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 버랜지나_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `805603cff160` | `버랜지나_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 버랜지나_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `8db3c53a9fb5` | `버랜지나_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 버랜지나_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `2d1d05b80eb1` | `버랜지나_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 버랜지나_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `90a76255d3fc` | `버랜지나_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 버랜지나_light_glossy_promo_f.webp | `casual1-prompt.txt` | 683 | `145444b26637` | `버랜지나_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 버랜지나_light_glossy_promo_f.webp | `casual2-prompt.txt` | 759 | `b547d481fcc8` | `버랜지나_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 버랜지나_light_glossy_promo_f.webp | `casual3-prompt.txt` | 791 | `1b4d98c6103c` | `버랜지나_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 비키니 | a 1950s pin-up bikini with a high-waisted bottom and a halter top |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 bikini · 드러내기 high-cut leg, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 bodysuit + leggings · 드러내기 side cutouts, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 시골 역 | a small rural station with a wooden bench and a single platform |
| 역할 | — |  |
| 의상 | 웨딩 · 2부 미니드레스 | a short beaded after-party wedding dress |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 dress · 드러내기 mini length, plunging neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit
