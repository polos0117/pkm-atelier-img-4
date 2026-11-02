# 앤티골 (0631 · Heatmor) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7ac5e2d · 2026-11-02T12:21:22.692Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 631 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 409 | `e0d5822b4e00` | `앤티골_light_glossy_promo_f.webp` |
| ② | heavy | ① 앤티골_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `1932dbee58d7` | `앤티골_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 앤티골_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `3145229d6651` | `앤티골_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 앤티골_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `d0dbec026cab` | `앤티골_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 앤티골_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `1c012b93ca20` | `앤티골_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 앤티골_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `f18e22025f45` | `앤티골_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 앤티골_light_glossy_promo_f.webp | `casual1-prompt.txt` | 789 | `052e771e9126` | `앤티골_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 앤티골_light_glossy_promo_f.webp | `casual2-prompt.txt` | 626 | `d7c7d1817f2f` | `앤티골_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 앤티골_light_glossy_promo_f.webp | `casual3-prompt.txt` | 706 | `b6303b793faa` | `앤티골_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 빗 · 머리를 빗는다 | brushes her hair with a hairbrush |

옷 종류 leggings + sweater · 드러내기 strapless top, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · environmental · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 드러내기 one-shoulder cut, bare midriff · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 tank · 드러내기 cropped hem, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit
