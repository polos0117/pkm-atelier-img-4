# 비조푸 (0619 · Mienfoo) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 4ac0589 · 2026-11-01T23:02:07.504Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 619 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 461 | `0a12c4182404` | `비조푸_light_glossy_promo_f.webp` |
| ② | heavy | ① 비조푸_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `7a92a0606db5` | `비조푸_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 비조푸_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `ff9cfdeb8782` | `비조푸_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 비조푸_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `226e2b2aed91` | `비조푸_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 비조푸_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `44c7a44ad977` | `비조푸_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 비조푸_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `a7d8b7921dc6` | `비조푸_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 비조푸_light_glossy_promo_f.webp | `casual1-prompt.txt` | 708 | `711ee6e2ae3b` | `비조푸_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 비조푸_light_glossy_promo_f.webp | `casual2-prompt.txt` | 738 | `b00ecf9ebab3` | `비조푸_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 비조푸_light_glossy_promo_f.webp | `casual3-prompt.txt` | 698 | `e17c8e2b0061` | `비조푸_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 케이블카 | a cable car cabin over a misty valley |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 bodysuit + leggings · 드러내기 mini length, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 lingerie_set + shirt · 드러내기 high-cut leg, plunging neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 수영복 · 트라이앵글 비키니 | a triangle bikini with slider cups and tie-side bottoms |
| 몸 자세 · 구도 | 쪼그려 앉기 · waist_up · 옆모습 | crouching low on her heels |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 드러내기 halter neck, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit
