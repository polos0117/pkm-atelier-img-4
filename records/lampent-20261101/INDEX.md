# 램프라 (0608 · Lampent) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 f07f388 · 2026-11-01T13:54:08.604Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 608 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 401 | `baa6c68962c8` | `램프라_light_glossy_promo_f.webp` |
| ② | heavy | ① 램프라_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `f6bd600597de` | `램프라_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 램프라_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `3a5a64ef76c2` | `램프라_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 램프라_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `fa8aa7f2a817` | `램프라_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 램프라_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `22dfeac02f8d` | `램프라_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 램프라_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `8df044eaea0d` | `램프라_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 램프라_light_glossy_promo_f.webp | `casual1-prompt.txt` | 732 | `61625a72b387` | `램프라_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 램프라_light_glossy_promo_f.webp | `casual2-prompt.txt` | 736 | `ee92353f37be` | `램프라_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 램프라_light_glossy_promo_f.webp | `casual3-prompt.txt` | 671 | `c74aab36fece` | `램프라_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 카메라 · 사진을 찍는다 | raises a camera to her eye to take a photo |

옷 종류 tank · 드러내기 off-shoulder neckline, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 경찰 코스튬 | a fitted navy police-style party costume with a short-brimmed cap and a short-sleeved button shirt, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 빗 · 머리를 빗는다 | brushes her hair with a hairbrush |

옷 종류 shirt · 드러내기 mini length, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 작은 가게 | a small shop — a bookstore, record store or plant shop — with crowded shelves |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 꽃 몇 송이 · 꽃 줄기를 다듬는다 | trims the stems of a few loose flower stems on the worktable |

옷 종류 dress · 드러내기 off-shoulder neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
