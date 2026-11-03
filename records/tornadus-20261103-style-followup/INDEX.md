# 토네로스 (0641 · Tornadus) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 91f03e6 · 2026-11-03T03:35:17.616Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 641 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 676 | `c26c91d2bd6a` | `토네로스_light_glossy_promo_f.webp` |
| ② | heavy | ① 토네로스_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `21323fc0181c` | `토네로스_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 토네로스_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `5c470f8401a2` | `토네로스_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 토네로스_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `570ffa88fe2f` | `토네로스_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 토네로스_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `255dd4ee1e73` | `토네로스_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 토네로스_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `ebdbf575a057` | `토네로스_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 토네로스_light_glossy_promo_f.webp | `casual1-prompt.txt` | 672 | `931ccaaeba35` | `토네로스_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 토네로스_light_glossy_promo_f.webp | `casual2-prompt.txt` | 766 | `d776e30b2940` | `토네로스_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 토네로스_light_glossy_promo_f.webp | `casual3-prompt.txt` | 648 | `a0b436939153` | `토네로스_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 야외 공연장 | an outdoor theatre of tiered seats facing a stage |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 옆모습 | kneeling on the ground |
| 손 · 소품 동작 | prop · prop · 카메라 · 찍은 사진을 확인한다 | checks the photo on the back screen of a camera at chest height |

옷 종류 bodysuit + leggings · 드러내기 halter neck, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 shorts · 드러내기 side cutouts, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바닷가 산책길 | a rocky coast path with tide pools |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 3/4 정면 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 드러내기 one-shoulder cut, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit
