# 배바닐라 (0584 · Vanilluxe) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bf5cd6b · 2026-10-31T06:02:08.734Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 584 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 404 | `4a6c5496ee6a` | `배바닐라_light_glossy_promo_f.webp` |
| ② | heavy | ① 배바닐라_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `90e863eee6ac` | `배바닐라_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 배바닐라_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `5af2a1cfb52b` | `배바닐라_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 배바닐라_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `b2ed4a190dc2` | `배바닐라_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 배바닐라_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `3e484d19913e` | `배바닐라_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 배바닐라_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `d4e987c02194` | `배바닐라_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 배바닐라_light_glossy_promo_f.webp | `casual1-prompt.txt` | 736 | `63ffe21dc7bf` | `배바닐라_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 배바닐라_light_glossy_promo_f.webp | `casual2-prompt.txt` | 743 | `56a788684006` | `배바닐라_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 배바닐라_light_glossy_promo_f.webp | `casual3-prompt.txt` | 673 | `7d2e5a09e307` | `배바닐라_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 마을 | a small town square of the Pokémon world with a fountain, flower beds and tiled roofs |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 아이스크림 · 아이스크림을 든다 | holds an ice cream cone at chest height |

옷 종류 shirt · 드러내기 halter neck, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 미래풍 스파 | a futuristic spa of white curves and soft light |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 lingerie_set + shirt · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 턱시도 재킷 + 캐미솔 + 정장 바지 | a sharp tuxedo jacket over a silk camisole with tailored trousers |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 내려놓는다 | sets a cup down on the surface in front of her |

옷 종류 jacket + tank + trousers · 드러내기 mini length, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit
