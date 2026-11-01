# 탱그릴 (0592 · Frillish) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 64eb073 · 2026-11-01T00:01:26.537Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 592 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 407 | `8bdaa5008dcd` | `탱그릴_light_glossy_promo_f.webp` |
| ② | heavy | ① 탱그릴_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `a1b12ffad71a` | `탱그릴_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 탱그릴_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `25caac142c36` | `탱그릴_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 탱그릴_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `d9fe5cffa3f5` | `탱그릴_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 탱그릴_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `dbe10ee45db8` | `탱그릴_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 탱그릴_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `ed22741081c9` | `탱그릴_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 탱그릴_light_glossy_promo_f.webp | `casual1-prompt.txt` | 786 | `08f8f20c8395` | `탱그릴_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 탱그릴_light_glossy_promo_f.webp | `casual2-prompt.txt` | 717 | `72d3814bedbc` | `탱그릴_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 탱그릴_light_glossy_promo_f.webp | `casual3-prompt.txt` | 743 | `2534b4d4d05f` | `탱그릴_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 화석 발굴지 | a fossil excavation site with gridded trays under a canvas shade |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 bikini · 드러내기 high-cut leg, plunging neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 체육관·복싱장 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 역할 | — |  |
| 의상 | 서브컬처 · 스케이터 | skater — a cropped hoodie, low-slung cargo shorts and high socks |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 농구공 · 공을 옆구리에 낀다 | tucks a basketball under one arm against her hip |

옷 종류 shorts + sweater · 드러내기 bare midriff, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 목욕 차림 · 페슈테말 | a striped cotton peshtemal wrapped like a dress |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 반죽 그릇과 거품기 · 반죽을 섞는다 | mixes the batter in a mixing bowl of batter and a whisk on the worktable |

옷 종류 dress · 드러내기 high thigh slit, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
