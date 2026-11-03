# 제크로무 (0644 · Zekrom) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 91f03e6 · 2026-11-03T03:50:42.803Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 644 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 411 | `dd7ddb3ba9e7` | `제크로무_light_glossy_promo_f.webp` |
| ② | heavy | ① 제크로무_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `eb3200ecc6c2` | `제크로무_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 제크로무_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `7ffdd0032b85` | `제크로무_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 제크로무_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `c8e39d5fe55c` | `제크로무_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 제크로무_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `69d86a00c9c7` | `제크로무_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 제크로무_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `90d6fbaba982` | `제크로무_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 제크로무_light_glossy_promo_f.webp | `casual1-prompt.txt` | 696 | `8ea5dd95f5ff` | `제크로무_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 제크로무_light_glossy_promo_f.webp | `casual2-prompt.txt` | 711 | `2eb4e90db2d1` | `제크로무_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 제크로무_light_glossy_promo_f.webp | `casual3-prompt.txt` | 702 | `dd8d975abcd0` | `제크로무_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 선글라스 · 접은 선글라스를 든다 | holds folded a pair of sunglasses by one arm |

옷 종류 dress + slip · 드러내기 open back, halter neck · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · prop · 카메라 · 찍은 사진을 확인한다 | checks the photo on the back screen of a camera at chest height |

옷 종류 bodysuit + leggings · 드러내기 cropped hem, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 자동 — 계열 안에서 장면에 맞게 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 몸 자세 · 구도 | 걷기 · chest_up · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 vest · 드러내기 bare midriff, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit
