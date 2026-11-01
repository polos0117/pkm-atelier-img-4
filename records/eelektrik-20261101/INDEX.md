# 저리릴 (0603 · Eelektrik) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 8a98025 · 2026-11-01T11:43:56.903Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 603 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 392 | `b623d34f0185` | `저리릴_light_glossy_promo_f.webp` |
| ② | heavy | ① 저리릴_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `22654a86ff48` | `저리릴_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 저리릴_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `dd23fbceaa0b` | `저리릴_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 저리릴_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `502b892a3191` | `저리릴_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 저리릴_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `08f3dfb30611` | `저리릴_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 저리릴_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `38dfd926ef0a` | `저리릴_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 저리릴_light_glossy_promo_f.webp | `casual1-prompt.txt` | 680 | `645eada5fa05` | `저리릴_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 저리릴_light_glossy_promo_f.webp | `casual2-prompt.txt` | 735 | `64385cf6e174` | `저리릴_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 저리릴_light_glossy_promo_f.webp | `casual3-prompt.txt` | 816 | `31a6d0728014` | `저리릴_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 롤러장 | a roller rink under coloured lights |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 수영복 | a 1950s high-waisted pin-up swimsuit |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 물병 · 물병을 든다 | holds a water bottle at chest height |

옷 종류 swimsuit · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 토트백 · 가방끈을 어깨에 걸쳐 잡는다 | holds the strap of a canvas tote bag on her shoulder |

옷 종류 dress · 드러내기 halter neck, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 캠프장 | a quiet campsite with a small tent and a cooking kit |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 기대 눕기 · chest_up · 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 swimsuit · 드러내기 high-cut leg, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit
