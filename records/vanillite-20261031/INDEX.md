# 바닐프티 (0582 · Vanillite) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 58bada8 · 2026-10-31T05:21:06.719Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 582 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 394 | `ea59983dbebe` | `바닐프티_light_glossy_promo_f.webp` |
| ② | heavy | ① 바닐프티_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `eb93ad05cca6` | `바닐프티_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 바닐프티_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `946afafcc0ed` | `바닐프티_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 바닐프티_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `3288c05c37c3` | `바닐프티_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 바닐프티_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `2d3a3e2ada3d` | `바닐프티_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 바닐프티_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `79d4a7d8a6f0` | `바닐프티_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 바닐프티_light_glossy_promo_f.webp | `casual1-prompt.txt` | 761 | `40b154818297` | `바닐프티_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 바닐프티_light_glossy_promo_f.webp | `casual2-prompt.txt` | 718 | `65a8e5034bca` | `바닐프티_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 바닐프티_light_glossy_promo_f.webp | `casual3-prompt.txt` | 640 | `ac162c36e6dc` | `바닐프티_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 성 계단 | the grand staircase of an old castle |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · environmental · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | rail · hair_tuck |  |

옷 종류 bikini · 드러내기 high-cut leg, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 불꽃놀이 강변 | a riverside seating area waiting for festival fireworks |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 불꽃 막대 · 불꽃 막대를 들어 올린다 | holds a lit sparkler up beside her face |

옷 종류 lingerie_set · 드러내기 halter neck, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 jumpsuit · 드러내기 mini length, high thigh slit · 장면 칸 첫머리 action · 직접 입력 scene, outfit
