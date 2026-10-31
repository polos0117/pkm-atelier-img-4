# 바닐리치 (0583 · Vanillish) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 58bada8 · 2026-10-31T05:21:06.898Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 583 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 395 | `5a5fb9df77c9` | `바닐리치_light_glossy_promo_f.webp` |
| ② | heavy | ① 바닐리치_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `63c04f9db904` | `바닐리치_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 바닐리치_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `66dd8743d979` | `바닐리치_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 바닐리치_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `9367a962650a` | `바닐리치_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 바닐리치_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `afd227174601` | `바닐리치_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 바닐리치_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `f4c5c2905e4c` | `바닐리치_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 바닐리치_light_glossy_promo_f.webp | `casual1-prompt.txt` | 743 | `217094c8cfe7` | `바닐리치_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 바닐리치_light_glossy_promo_f.webp | `casual2-prompt.txt` | 726 | `ca5cb351f303` | `바닐리치_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 바닐리치_light_glossy_promo_f.webp | `casual3-prompt.txt` | 667 | `a5a0ef63007b` | `바닐리치_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 서커스 천막 | a circus tent ring under a striped canopy |
| 역할 | — |  |
| 의상 | 레트로 · 60년대 리비에라 수영복 | a 1960s jet-set one-piece swimsuit with a headscarf and cat-eye sunglasses |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 swimsuit · 드러내기 high-cut leg, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 리조트 라군 데크 | a resort lagoon deck with stacked towels and lounge cushions |
| 역할 | — |  |
| 의상 | 평상복 · 터틀넥 + 퀼팅 조끼 + 바지 | a fine knit turtleneck under a quilted vest with straight trousers |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 옆모습 | kneeling on the ground |
| 손 · 소품 동작 | prop · prop · 몬스터볼 · 몬스터볼을 천으로 닦는다 | polishes a Poké Ball with a soft cloth |

옷 종류 trousers + vest · 드러내기 cropped hem, one-shoulder cut · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 드러내기 strapless top, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit
