# 삼삼드래 (0635 · Hydreigon) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5b29775 · 2026-11-02T13:51:07.492Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 635 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 427 | `3271284fb8cb` | `삼삼드래_light_glossy_promo_f.webp` |
| ② | heavy | ① 삼삼드래_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `a2611177f5a6` | `삼삼드래_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 삼삼드래_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `8a7b627b524f` | `삼삼드래_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 삼삼드래_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `f9ffe156942b` | `삼삼드래_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 삼삼드래_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `4a40c587ac83` | `삼삼드래_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 삼삼드래_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `8ccc575cba5e` | `삼삼드래_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 삼삼드래_light_glossy_promo_f.webp | `casual1-prompt.txt` | 664 | `4aa0fda52267` | `삼삼드래_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 삼삼드래_light_glossy_promo_f.webp | `casual2-prompt.txt` | 736 | `1892606bc9e7` | `삼삼드래_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 삼삼드래_light_glossy_promo_f.webp | `casual3-prompt.txt` | 667 | `304278ee0221` | `삼삼드래_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 골목 | a narrow city alley with hanging signboards and wet pavement |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 옆모습 | crouching low on her heels |
| 손 · 소품 동작 | prop · natural · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 crop_top + skirt · 드러내기 cropped hem, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 마을 지붕 테라스 | a rooftop terrace above a Pokémon-world harbor town |
| 역할 | — |  |
| 의상 | 전통 의상 · 한복 · 정장 | a formal Korean hanbok — short jeogori with goreum bow and white dongjeong collar over a full high-wrapped chima; not hanfu |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 traditional · 드러내기 high thigh slit, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 비키니 | a 1950s pin-up bikini with a high-waisted bottom and a halter top |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 노트와 펜 · 노트에 쓴다 | writes in a notebook with a pen on the table |

옷 종류 bikini · 드러내기 high-cut leg, bare midriff · 장면 칸 첫머리 action · 직접 입력 scene, outfit
