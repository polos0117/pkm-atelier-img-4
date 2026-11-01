# 코고미 (0613 · Cubchoo) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 20db2e1 · 2026-11-01T15:05:24.744Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 613 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 403 | `1925e60b275e` | `코고미_light_glossy_promo_f.webp` |
| ② | heavy | ① 코고미_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `7871aee862de` | `코고미_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 코고미_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `7da82993e289` | `코고미_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 코고미_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `ce6a848faeb0` | `코고미_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 코고미_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `d2ca987f956a` | `코고미_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 코고미_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `a9d3cdb2658a` | `코고미_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 코고미_light_glossy_promo_f.webp | `casual1-prompt.txt` | 691 | `62a7e8e0285a` | `코고미_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 코고미_light_glossy_promo_f.webp | `casual2-prompt.txt` | 746 | `f82c41a17cdb` | `코고미_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 코고미_light_glossy_promo_f.webp | `casual3-prompt.txt` | 732 | `950cda952059` | `코고미_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 핀업 비키니 | a 1950s pin-up bikini with a high-waisted bottom and a halter top |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 bikini · 드러내기 high-cut leg, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 헤드폰 · 헤드폰을 두 손으로 귀에 누른다 | presses over-ear headphones to her ears with both hands |

옷 종류 crop_top + skirt · 드러내기 strapless top, mini length · 장면 칸 첫머리 light

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 blouse · 드러내기 cropped hem, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
