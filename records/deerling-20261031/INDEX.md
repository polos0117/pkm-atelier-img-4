# 사철록 (0585 · Deerling) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bf5cd6b · 2026-10-31T06:02:08.907Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 585 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 423 | `6d913599b947` | `사철록_light_glossy_promo_f.webp` |
| ② | heavy | ① 사철록_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `fb58362b28a7` | `사철록_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 사철록_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `e19ae85397b7` | `사철록_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 사철록_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `20a7a480fb1d` | `사철록_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 사철록_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `68f3fc5188aa` | `사철록_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 사철록_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `3cd1186c638c` | `사철록_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 사철록_light_glossy_promo_f.webp | `casual1-prompt.txt` | 797 | `7189855a8f66` | `사철록_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 사철록_light_glossy_promo_f.webp | `casual2-prompt.txt` | 775 | `2fe5c9d86b8a` | `사철록_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 사철록_light_glossy_promo_f.webp | `casual3-prompt.txt` | 669 | `db0600ffb4a0` | `사철록_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 | a village market stall piled with fresh berries |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 blouse · 드러내기 off-shoulder neckline, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 서브컬처 · 스케이터 | skater — a cropped hoodie, low-slung cargo shorts and high socks |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 물병 · 물병을 든다 | holds a water bottle at chest height |

옷 종류 shorts + sweater · 드러내기 cropped hem, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 미래풍 스파 | a futuristic spa of white curves and soft light |
| 역할 | — |  |
| 의상 | 레트로 · 80년대 에어로빅 | an 1980s high-cut aerobics leotard over shiny tights with leg warmers and a headband |
| 몸 자세 · 구도 | 기대 눕기 · full_body · 정면 | reclining on her back |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 leggings · 드러내기 side cutouts, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
