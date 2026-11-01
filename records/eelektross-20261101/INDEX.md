# 저리더프 (0604 · Eelektross) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 1bc63d1 · 2026-11-01T12:38:44.660Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 604 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 408 | `15bb411f9184` | `저리더프_light_glossy_promo_f.webp` |
| ② | heavy | ① 저리더프_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `e42101b34742` | `저리더프_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 저리더프_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `04b362aebe5b` | `저리더프_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 저리더프_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `2c3b6ba0776e` | `저리더프_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 저리더프_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `1fac5cdd0018` | `저리더프_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 저리더프_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `0798f80fa0ce` | `저리더프_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 저리더프_light_glossy_promo_f.webp | `casual1-prompt.txt` | 694 | `dd6435e9027c` | `저리더프_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 저리더프_light_glossy_promo_f.webp | `casual2-prompt.txt` | 736 | `f0315ebb59fe` | `저리더프_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 저리더프_light_glossy_promo_f.webp | `casual3-prompt.txt` | 781 | `2469393b9ec7` | `저리더프_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호숫가 | a lakeside of flat rocks and still water |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 apron · 드러내기 one-shoulder cut, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 접부채 · 부채로 얼굴을 가린다 | lifts a folding fan open to just below her eyes |

옷 종류 lingerie_set + skirt · 드러내기 strapless top, high-cut leg · 장면 칸 첫머리 light · 직접 입력 scene

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 축제 거리 | a festival street of lanterns, food stalls and paper decorations |
| 역할 | — |  |
| 의상 | 홈웨어 · 아침 로브 | a loosely tied robe |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · waist_up · 뒤 3/4 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 드러내기 open back, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit
