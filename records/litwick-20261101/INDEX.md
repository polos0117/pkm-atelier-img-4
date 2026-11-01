# 불켜미 (0607 · Litwick) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 b373b4d · 2026-11-01T13:28:08.048Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 607 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 394 | `1014077406e3` | `불켜미_light_glossy_promo_f.webp` |
| ② | heavy | ① 불켜미_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `3164c853af8e` | `불켜미_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 불켜미_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `c9ee80dec125` | `불켜미_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 불켜미_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `62e0864efb79` | `불켜미_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 불켜미_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `c855a8204cbc` | `불켜미_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 불켜미_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `48e37c030efb` | `불켜미_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 불켜미_light_glossy_promo_f.webp | `casual1-prompt.txt` | 823 | `1eba4e9949e2` | `불켜미_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 불켜미_light_glossy_promo_f.webp | `casual2-prompt.txt` | 662 | `74bfeb55d902` | `불켜미_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 불켜미_light_glossy_promo_f.webp | `casual3-prompt.txt` | 716 | `20304a4c6d84` | `불켜미_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 나무열매 바구니 · 나무열매 바구니를 팔에 건다 | carries a woven basket of berries in the crook of her arm |

옷 종류 crop_top + overalls · 드러내기 bare midriff, cropped hem · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 쇼핑몰 | a shopping mall atrium with a fountain and glass railings |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 dress · 드러내기 halter neck, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 가면무도회장 | a chandelier ballroom at a masquerade |
| 역할 | — |  |
| 의상 | 수영복 · 반두 비키니 | a bandeau bikini with a straight strapless top |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 bikini + crop_top · 드러내기 high-cut leg, plunging neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit
