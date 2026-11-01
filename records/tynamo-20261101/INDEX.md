# 저리어 (0602 · Tynamo) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 f49b02e · 2026-11-01T12:12:12.960Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 602 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 410 | `3241ef37aed4` | `저리어_light_glossy_promo_f.webp` |
| ② | heavy | ① 저리어_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `55fcd9e0a10d` | `저리어_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 저리어_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `92168982bc2a` | `저리어_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 저리어_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `d290bd1e963c` | `저리어_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 저리어_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `8b1d1c28bf2d` | `저리어_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 저리어_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `537dce105714` | `저리어_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 저리어_light_glossy_promo_f.webp | `casual1-prompt.txt` | 811 | `d73fcc7f6adb` | `저리어_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 저리어_light_glossy_promo_f.webp | `casual2-prompt.txt` | 796 | `7c4720c2bab7` | `저리어_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 저리어_light_glossy_promo_f.webp | `casual3-prompt.txt` | 666 | `447a99b7e8b5` | `저리어_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 박물관 | a Pokémon natural-history museum with display stands, a gallery and an archive room |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 jacket + trousers · 드러내기 side cutouts, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 레트로 우주비행사 | a retro space-age costume — a fitted white jumpsuit with silver trim and moon boots |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 가면 · 가면을 든다 | holds a masquerade mask on a stick up to her eyes |

옷 종류 jumpsuit · 드러내기 high thigh slit, plunging neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 선글라스 · 접은 선글라스를 든다 | holds folded a pair of sunglasses by one arm |

옷 종류 bodysuit + leggings · 드러내기 halter neck, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
