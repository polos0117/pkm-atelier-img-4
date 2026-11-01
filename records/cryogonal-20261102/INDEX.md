# 프리지오 (0615 · Cryogonal) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 3fc0641 · 2026-11-01T18:43:34.673Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 615 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 388 | `19f4a4beb751` | `프리지오_light_glossy_promo_f.webp` |
| ② | heavy | ① 프리지오_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `3dbfa9d2548e` | `프리지오_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 프리지오_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `71361d8f6b88` | `프리지오_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 프리지오_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `947233b8f4bf` | `프리지오_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 프리지오_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `f844ec7fe4cb` | `프리지오_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 프리지오_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `0d23e72ab9bf` | `프리지오_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 프리지오_light_glossy_promo_f.webp | `casual1-prompt.txt` | 771 | `14433776c34a` | `프리지오_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 프리지오_light_glossy_promo_f.webp | `casual2-prompt.txt` | 808 | `770521e8948f` | `프리지오_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 프리지오_light_glossy_promo_f.webp | `casual3-prompt.txt` | 716 | `832d11cd8852` | `프리지오_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 물병 · 물을 마신다 | drinks from a water bottle |

옷 종류 leggings + tank · 드러내기 bare midriff, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 마술사 조수 | a stage magician's assistant costume — a sequined fitted leotard-style top, a short tailcoat, gloves and a small top hat |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 bodysuit · 드러내기 bare midriff, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 crop_top + skirt · 드러내기 side cutouts, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit
