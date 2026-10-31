# 뽀록나 (0591 · Amoonguss) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 93ac493 · 2026-10-31T17:27:58.809Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 591 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 386 | `23b6d5e88960` | `뽀록나_light_glossy_promo_f.webp` |
| ② | heavy | ① 뽀록나_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `125e081de250` | `뽀록나_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 뽀록나_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `b8adf169e630` | `뽀록나_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 뽀록나_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 251 | `207401e67116` | `뽀록나_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 뽀록나_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 257 | `73c95775601a` | `뽀록나_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 뽀록나_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 250 | `34f04f315ace` | `뽀록나_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 뽀록나_light_glossy_promo_f.webp | `casual1-prompt.txt` | 771 | `7f7704a0027a` | `뽀록나_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 뽀록나_light_glossy_promo_f.webp | `casual2-prompt.txt` | 686 | `ba8e18190ae3` | `뽀록나_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 뽀록나_light_glossy_promo_f.webp | `casual3-prompt.txt` | 826 | `a589fec297d8` | `뽀록나_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 robe + slip · 드러내기 strapless top, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 별빛 무대 | a stage under a painted night sky of crystal stars |
| 역할 | — |  |
| 의상 | 란제리풍 · 브라렛 + 하이웨이스트 | a soft-cup bralette with wide straps and matching high-waisted bottoms |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 crop_top · 드러내기 open back, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬센터 로비 | the bright lobby of a Pokémon Center with a reception counter, sofas and potted plants |
| 역할 | — |  |
| 의상 | 직업복 · 글래머 오피스룩 | glamorous tailored workwear — a fitted vest over a silk blouse and a high-waisted pencil skirt |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 blouse + skirt + vest · 드러내기 off-shoulder neckline, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit
