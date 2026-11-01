# 벰크 (0606 · Beheeyem) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 b373b4d · 2026-11-01T13:20:41.634Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 606 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 409 | `4f763be4951c` | `벰크_light_glossy_promo_f.webp` |
| ② | heavy | ① 벰크_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `36672d0344a5` | `벰크_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 벰크_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `5dc12cbee59b` | `벰크_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 벰크_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `92f7c0dbda1a` | `벰크_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 벰크_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `002f5596350f` | `벰크_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 벰크_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `e979960d3b76` | `벰크_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 벰크_light_glossy_promo_f.webp | `casual1-prompt.txt` | 796 | `5326a5863f8f` | `벰크_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 벰크_light_glossy_promo_f.webp | `casual2-prompt.txt` | 782 | `1e23154cdb7d` | `벰크_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 벰크_light_glossy_promo_f.webp | `casual3-prompt.txt` | 703 | `009537de0a7d` | `벰크_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 shorts + sweater · 드러내기 cropped hem, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 가면무도회장 | a chandelier ballroom at a masquerade |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 jumpsuit · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 시장 | a busy street market of food stalls and strung bulbs |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 드러내기 cropped hem, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit
