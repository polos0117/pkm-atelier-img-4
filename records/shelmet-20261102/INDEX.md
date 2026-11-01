# 쪼마리 (0616 · Shelmet) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 454fcdb · 2026-11-01T21:29:13.174Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 616 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 414 | `1c5c69623891` | `쪼마리_light_glossy_promo_f.webp` |
| ② | heavy | ① 쪼마리_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `c7f6ee029be9` | `쪼마리_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 쪼마리_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `860081f0f1f3` | `쪼마리_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 쪼마리_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `e0b324419051` | `쪼마리_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 쪼마리_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `9be6ced89b21` | `쪼마리_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 쪼마리_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `72bdfa5ca86b` | `쪼마리_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 쪼마리_light_glossy_promo_f.webp | `casual1-prompt.txt` | 707 | `3c624010b8ca` | `쪼마리_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 쪼마리_light_glossy_promo_f.webp | `casual2-prompt.txt` | 739 | `e34c35e1f476` | `쪼마리_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 쪼마리_light_glossy_promo_f.webp | `casual3-prompt.txt` | 676 | `6f811d3b363f` | `쪼마리_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 dress + slip · 드러내기 high thigh slit, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 서커스 천막 | a circus tent ring under a striped canopy |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 lingerie_set + skirt · 드러내기 high-cut leg, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 jumpsuit · 드러내기 high thigh slit, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
