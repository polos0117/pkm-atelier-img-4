# 디헤드 (0634 · Zweilous) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5b29775 · 2026-11-02T13:51:07.359Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 634 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 397 | `59aaf25251f6` | `디헤드_light_glossy_promo_f.webp` |
| ② | heavy | ① 디헤드_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `054fc7250346` | `디헤드_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 디헤드_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `cff673fd66a8` | `디헤드_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 디헤드_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `01a7802888e0` | `디헤드_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 디헤드_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `3d64e8b03285` | `디헤드_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 디헤드_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `34145716567c` | `디헤드_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 디헤드_light_glossy_promo_f.webp | `casual1-prompt.txt` | 692 | `1165213ba329` | `디헤드_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 디헤드_light_glossy_promo_f.webp | `casual2-prompt.txt` | 633 | `d2677e3b2767` | `디헤드_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 디헤드_light_glossy_promo_f.webp | `casual3-prompt.txt` | 808 | `83aa255f7d70` | `디헤드_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 골목 | a narrow city alley with hanging signboards and wet pavement |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 bodysuit + leggings · 드러내기 cropped hem, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 란제리풍 · 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |
| 몸 자세 · 구도 | 걷기 · environmental · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 드러내기 high thigh slit, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 직업복 · 자동 — 계열 안에서 장면에 맞게 | practical clothing for her Pokémon-world job, readable through its tools |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 overalls + tank · 드러내기 bare midriff, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit
