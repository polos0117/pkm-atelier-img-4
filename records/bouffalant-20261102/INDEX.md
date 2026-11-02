# 버프론 (0626 · Bouffalant) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 8accb4e · 2026-11-02T09:12:25.039Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 626 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 406 | `e42215083ac8` | `버프론_light_glossy_promo_f.webp` |
| ② | heavy | ① 버프론_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `ec0be1b248e3` | `버프론_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 버프론_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `0447b20175e0` | `버프론_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 버프론_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 244 | `5a250207670b` | `버프론_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 버프론_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 250 | `d259f438263a` | `버프론_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 버프론_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 243 | `add933a8d317` | `버프론_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 버프론_light_glossy_promo_f.webp | `casual1-prompt.txt` | 719 | `f69a5538c115` | `버프론_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 버프론_light_glossy_promo_f.webp | `casual2-prompt.txt` | 630 | `a77bdd859d3d` | `버프론_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 버프론_light_glossy_promo_f.webp | `casual3-prompt.txt` | 785 | `981cba620273` | `버프론_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 별빛 무대 | a stage under a painted night sky of crystal stars |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 bikini · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 드러내기 high thigh slit, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 비행 포켓몬 승강장 | an open landing terrace for Flying-Pokémon travel, with harness racks and a wind sock |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 coat + dress · 드러내기 off-shoulder neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
