# 수리둥보 (0627 · Rufflet) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 8accb4e · 2026-11-02T09:12:25.167Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 627 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 400 | `d22f5cadbec3` | `수리둥보_light_glossy_promo_f.webp` |
| ② | heavy | ① 수리둥보_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `20de7e75dc1a` | `수리둥보_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 수리둥보_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `73b695e7996f` | `수리둥보_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 수리둥보_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `e816922c0bce` | `수리둥보_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 수리둥보_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `213681e196c6` | `수리둥보_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 수리둥보_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `789764211e22` | `수리둥보_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 수리둥보_light_glossy_promo_f.webp | `casual1-prompt.txt` | 734 | `0e6876f5f7e1` | `수리둥보_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 수리둥보_light_glossy_promo_f.webp | `casual2-prompt.txt` | 695 | `6ae3111db41f` | `수리둥보_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 수리둥보_light_glossy_promo_f.webp | `casual3-prompt.txt` | 769 | `e780a6e0c502` | `수리둥보_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 bodysuit + leggings · 드러내기 bare midriff, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 별빛 무대 | a stage under a painted night sky of crystal stars |
| 역할 | — |  |
| 의상 | 레트로 · 90년대 윈드브레이커 + 트랙 팬츠 | a color-blocked 1990s windbreaker with matching track pants |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 jacket + trousers · 드러내기 cropped hem, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 jumpsuit · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene, outfit
