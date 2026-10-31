# 슈바르고 (0589 · Escavalier) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 884227a · 2026-10-31T17:10:21.905Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 589 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 402 | `9ff12fe6c273` | `슈바르고_light_glossy_promo_f.webp` |
| ② | heavy | ① 슈바르고_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `3414aa0cb1cd` | `슈바르고_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 슈바르고_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `1a768321e4ee` | `슈바르고_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 슈바르고_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `9cf931bf5f7f` | `슈바르고_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 슈바르고_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `7d7cf744f599` | `슈바르고_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 슈바르고_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `04b6109d081c` | `슈바르고_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 슈바르고_light_glossy_promo_f.webp | `casual1-prompt.txt` | 750 | `57ee91112cef` | `슈바르고_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 슈바르고_light_glossy_promo_f.webp | `casual2-prompt.txt` | 745 | `3132c9b961fd` | `슈바르고_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 슈바르고_light_glossy_promo_f.webp | `casual3-prompt.txt` | 706 | `6e23b6a35b73` | `슈바르고_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 불꽃놀이 강변 | a riverside seating area waiting for festival fireworks |
| 역할 | — |  |
| 의상 | 평상복 · 롱코트 + 머플러 | a long wool coat and a knitted scarf |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 불꽃 막대 · 불꽃 막대를 들어 올린다 | holds a lit sparkler up beside her face |

옷 종류 coat · 드러내기 bare midriff, cropped hem · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 crop_top + overalls · 드러내기 open back, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 밤 천문대 | a night observatory under an open dome |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 uniform · 드러내기 cropped hem, bare midriff · 장면 칸 첫머리 light · 직접 입력 scene, outfit
