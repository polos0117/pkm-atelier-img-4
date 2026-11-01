# 툰베어 (0614 · Beartic) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 3fc0641 · 2026-11-01T18:25:53.033Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 614 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 408 | `bd84880a467b` | `툰베어_light_glossy_promo_f.webp` |
| ② | heavy | ① 툰베어_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `62bc799164a1` | `툰베어_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 툰베어_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `94da8bac64d6` | `툰베어_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 툰베어_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `68613579a205` | `툰베어_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 툰베어_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `6581c7dba171` | `툰베어_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 툰베어_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `29b2437dd5a9` | `툰베어_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 툰베어_light_glossy_promo_f.webp | `casual1-prompt.txt` | 712 | `cf3a6214d5ab` | `툰베어_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 툰베어_light_glossy_promo_f.webp | `casual2-prompt.txt` | 727 | `a461360ffb7f` | `툰베어_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 툰베어_light_glossy_promo_f.webp | `casual3-prompt.txt` | 647 | `83ca1247412e` | `툰베어_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 레트로 · 60년대 리비에라 수영복 | a 1960s jet-set one-piece swimsuit with a headscarf and cat-eye sunglasses |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 swimsuit · 드러내기 high-cut leg, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 성 계단 | the grand staircase of an old castle |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 서기 · waist_up · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 | a city rooftop with a water tank, string lights and the skyline |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 비닐 무대 의상 | a vinyl stage costume with a glossy fitted jacket and boots |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jacket · 드러내기 halter neck, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
