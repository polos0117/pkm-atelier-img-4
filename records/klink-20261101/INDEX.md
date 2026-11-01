# 기어르 (0599 · Klink) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 ce4861f · 2026-11-01T05:35:00.172Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 599 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 394 | `a6045cc29df7` | `기어르_light_glossy_promo_f.webp` |
| ② | heavy | ① 기어르_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `8f25d732f933` | `기어르_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 기어르_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `d1d622391240` | `기어르_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 기어르_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `3a66f36b5c1e` | `기어르_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 기어르_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `6519802a7fe1` | `기어르_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 기어르_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `92b20d7eec03` | `기어르_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 기어르_light_glossy_promo_f.webp | `casual1-prompt.txt` | 773 | `7f94580568e3` | `기어르_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 기어르_light_glossy_promo_f.webp | `casual2-prompt.txt` | 759 | `5fd28497faff` | `기어르_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 기어르_light_glossy_promo_f.webp | `casual3-prompt.txt` | 647 | `4d5eb917f67f` | `기어르_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 양궁장 | an archery range of targets on a green field |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 물병 · 물병을 든다 | holds a water bottle at chest height |

옷 종류 crop_top + overalls · 드러내기 bare midriff, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 헤드폰 · 헤드폰을 두 손으로 귀에 누른다 | presses over-ear headphones to her ears with both hands |

옷 종류 lingerie_set · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 란제리풍 · 새틴 세트 | a satin lingerie set with a smooth bias-cut top and matching bottoms in a single deep colour |
| 몸 자세 · 구도 | 벽에 기대 서기 · environmental · 뒤 3/4 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 드러내기 high-cut leg, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit
