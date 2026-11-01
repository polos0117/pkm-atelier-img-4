# 전툴라 (0596 · Galvantula) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 6810453 · 2026-11-01T05:18:36.271Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 596 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 407 | `5605a0105f12` | `전툴라_light_glossy_promo_f.webp` |
| ② | heavy | ① 전툴라_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `38a5b1bd5d75` | `전툴라_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 전툴라_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `8d2497344075` | `전툴라_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 전툴라_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `f0d065fa2816` | `전툴라_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 전툴라_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `ea2cb45e7ffd` | `전툴라_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 전툴라_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `cfc0ad8650c4` | `전툴라_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 전툴라_light_glossy_promo_f.webp | `casual1-prompt.txt` | 732 | `a73ccffa2550` | `전툴라_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 전툴라_light_glossy_promo_f.webp | `casual2-prompt.txt` | 717 | `3fd49d6480da` | `전툴라_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 전툴라_light_glossy_promo_f.webp | `casual3-prompt.txt` | 820 | `3e3fd359b18e` | `전툴라_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 coat + dress · 드러내기 high thigh slit, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 bikini · 드러내기 high-cut leg, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · environmental · 뒤 3/4 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | rail · hair_tuck |  |

옷 종류 apron + shirt · 드러내기 mini length, cropped hem · 장면 칸 첫머리 place · 직접 입력 scene, outfit
