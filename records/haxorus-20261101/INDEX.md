# 액스라이즈 (0612 · Haxorus) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 20db2e1 · 2026-11-01T15:05:24.624Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 612 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 404 | `a62a7a373eda` | `액스라이즈_light_glossy_promo_f.webp` |
| ② | heavy | ① 액스라이즈_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `4716380d965b` | `액스라이즈_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 액스라이즈_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `bcc925728660` | `액스라이즈_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 액스라이즈_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `614c618756c5` | `액스라이즈_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 액스라이즈_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `10e7bfe0e3b9` | `액스라이즈_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 액스라이즈_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `d365b2452b79` | `액스라이즈_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 액스라이즈_light_glossy_promo_f.webp | `casual1-prompt.txt` | 688 | `2f42b1189cee` | `액스라이즈_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 액스라이즈_light_glossy_promo_f.webp | `casual2-prompt.txt` | 676 | `bb828a3a00f7` | `액스라이즈_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 액스라이즈_light_glossy_promo_f.webp | `casual3-prompt.txt` | 762 | `671448ae0c05` | `액스라이즈_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · prop · 스케치북 · 스케치한다 | sketches in a sketchbook and pencil |

옷 종류 bodysuit + leggings · 드러내기 mini length, cropped hem · 장면 칸 첫머리 action · 직접 입력 scene

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · three_quarter · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | edge_brace_both · edge_brace_both |  |

옷 종류 traditional · 드러내기 one-shoulder cut, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 dress + robe · 드러내기 high thigh slit, halter neck · 장면 칸 첫머리 detail · 직접 입력 scene
