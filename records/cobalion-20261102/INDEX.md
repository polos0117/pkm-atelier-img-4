# 코바르온 (0638 · Cobalion) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7328348 · 2026-11-02T14:46:54.448Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 638 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 424 | `3e0e7bf5f38d` | `코바르온_light_glossy_promo_f.webp` |
| ② | heavy | ① 코바르온_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `fe617ebc6010` | `코바르온_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 코바르온_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `2433fd8b8e94` | `코바르온_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 코바르온_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `12863325746a` | `코바르온_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 코바르온_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `94659739dee7` | `코바르온_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 코바르온_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `ac4ab6f67c15` | `코바르온_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 코바르온_light_glossy_promo_f.webp | `casual1-prompt.txt` | 733 | `c55cc70aec60` | `코바르온_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 코바르온_light_glossy_promo_f.webp | `casual2-prompt.txt` | 791 | `b4c1b15592ce` | `코바르온_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 코바르온_light_glossy_promo_f.webp | `casual3-prompt.txt` | 811 | `f7bb23223caf` | `코바르온_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 손거울 · 손거울을 본다 | holds a compact mirror open in front of her face |

옷 종류 lingerie_set + skirt · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 테마 행사장 | a themed costume event venue with props and a photo wall |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 shirt · 드러내기 strapless top, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 쇼핑몰 | a shopping mall atrium with a fountain and glass railings |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 레트로 우주비행사 | a retro space-age costume — a fitted white jumpsuit with silver trim and moon boots |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 아이스크림 · 아이스크림을 든다 | holds an ice cream cone at chest height |

옷 종류 jumpsuit · 드러내기 open back, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit
