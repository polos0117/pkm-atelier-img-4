# 비조도 (0620 · Mienshao) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 1d41ca2 · 2026-11-01T23:59:00.445Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 620 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 474 | `1b8f4285be3b` | `비조도_light_glossy_promo_f.webp` |
| ② | heavy | ① 비조도_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `92d4d817815a` | `비조도_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 비조도_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `d6a512c94969` | `비조도_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 비조도_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `924dda95fe46` | `비조도_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 비조도_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `fde032d438d5` | `비조도_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 비조도_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `bb7d2f71ce34` | `비조도_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 비조도_light_glossy_promo_f.webp | `casual1-prompt.txt` | 739 | `943757e8531a` | `비조도_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 비조도_light_glossy_promo_f.webp | `casual2-prompt.txt` | 743 | `53f44879fa6b` | `비조도_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 비조도_light_glossy_promo_f.webp | `casual3-prompt.txt` | 815 | `4ff756191a8a` | `비조도_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 동전 · 동전을 들어 보인다 | holds a single coin up between two fingers |

옷 종류 tank · 드러내기 bare midriff, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 칵테일 잔 · 잔을 입에 댄다 | brings a cocktail glass to her lips |

옷 종류 dress · 드러내기 off-shoulder neckline, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 온천 | an outdoor hot spring of a Pokémon-world mountain town, steam over smooth rocks |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 crop_top + overalls · 드러내기 cropped hem, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit
