# 탱탱겔 (0593 · Jellicent) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 64eb073 · 2026-11-01T00:04:20.207Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 593 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 432 | `385cdda9da6c` | `탱탱겔_light_glossy_promo_f.webp` |
| ② | heavy | ① 탱탱겔_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `6dd299adaa84` | `탱탱겔_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 탱탱겔_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `6c5a1e5d3a0d` | `탱탱겔_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 탱탱겔_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `4e08f478121f` | `탱탱겔_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 탱탱겔_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `3b2009b12fd5` | `탱탱겔_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 탱탱겔_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `83e7b75d3679` | `탱탱겔_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 탱탱겔_light_glossy_promo_f.webp | `casual1-prompt.txt` | 684 | `35cf851db9f5` | `탱탱겔_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 탱탱겔_light_glossy_promo_f.webp | `casual2-prompt.txt` | 755 | `268d9d261f8c` | `탱탱겔_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 탱탱겔_light_glossy_promo_f.webp | `casual3-prompt.txt` | 664 | `ef6902204636` | `탱탱겔_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 산장 | a mountain lodge with a front counter and a fireplace |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 바니 코스튬 | a retro casino bunny costume with a fitted one-piece, cuffs, bow-tie collar and rabbit-ear headband |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 swimsuit · 드러내기 high-cut leg, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 lingerie_set · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 콘테스트장 | a Pokémon Contest hall with a decorated stage, ribbon displays and audience seats |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 드러내기 cropped hem, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit
