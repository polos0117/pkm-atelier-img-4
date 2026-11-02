# 수리둥보 (0627 · Rufflet) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 37aca9f · 2026-11-02T10:35:32.390Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 627 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 407 | `1874e6467ced` | `수리둥보_light_glossy_promo_f.webp` |
| ② | heavy | ① 수리둥보_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `20de7e75dc1a` | `수리둥보_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 수리둥보_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `73b695e7996f` | `수리둥보_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 수리둥보_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `e816922c0bce` | `수리둥보_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 수리둥보_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `213681e196c6` | `수리둥보_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 수리둥보_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `789764211e22` | `수리둥보_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 수리둥보_light_glossy_promo_f.webp | `casual1-prompt.txt` | 694 | `e938603488cc` | `수리둥보_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 수리둥보_light_glossy_promo_f.webp | `casual2-prompt.txt` | 749 | `51f1d1525563` | `수리둥보_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 수리둥보_light_glossy_promo_f.webp | `casual3-prompt.txt` | 735 | `3f45d274b57a` | `수리둥보_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 레트로 · 90년대 윈드브레이커 + 트랙 팬츠 | a color-blocked 1990s windbreaker with matching track pants |
| 몸 자세 · 구도 | 벽에 기대 서기 · full_body · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | pocket · hair_tuck |  |

옷 종류 jacket + trousers · 드러내기 open back, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 코트 | an outdoor court for tennis or basketball |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 shirt · 드러내기 bare midriff, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 jumpsuit · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 —
