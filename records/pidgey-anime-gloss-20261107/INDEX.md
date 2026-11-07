# 구구 (0016 · Pidgey) — 지시문 묶음

화풍 `anime_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 10661ba · 2026-11-07T05:43:30.861Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 16 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 659 | `40cbc3c3855a` | `구구_light_anime_gloss_f.webp` |
| ② | casual1 | ① 구구_light_anime_gloss_f.webp | `casual1-prompt.txt` | 887 | `991b83c420eb` | `구구_anime_gloss_f_casual1.webp` |
| ③ | casual2 | ① 구구_light_anime_gloss_f.webp | `casual2-prompt.txt` | 912 | `95bd47f59667` | `구구_anime_gloss_f_casual2.webp` |
| ④ | casual3 | ① 구구_light_anime_gloss_f.webp | `casual3-prompt.txt` | 951 | `c19ed746e45b` | `구구_anime_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 구구_light_anime_gloss_f.webp | `casual4-prompt.txt` | 776 | `c62698122faf` | `구구_anime_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 구구_light_anime_gloss_f.webp | `casual5-prompt.txt` | 811 | `670b168511e4` | `구구_anime_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 구구_light_anime_gloss_f.webp | `casual6-prompt.txt` | 952 | `044f3d821d81` | `구구_anime_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 구구_light_anime_gloss_f.webp | `casual7-prompt.txt` | 892 | `3dce88f3e904` | `구구_anime_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 정면 | lying on her side |
| 손 · 소품 동작 | behind_head · floor_brace |  |

옷 종류 lingerie_set + shirt · 드러내기 bare midriff, plunging neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 평상복 · 후디 + 레깅스 | a cropped hoodie and leggings |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 leggings + sweater · 드러내기 off-shoulder neckline, cropped hem · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 crop_top + overalls · 드러내기 halter neck, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 골목 | a narrow city alley with hanging signboards and wet pavement |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 bodysuit + leggings · 드러내기 strapless top, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 밤 택시 | the back seat of a taxi at night, city lights streaking past |
| 역할 | — |  |
| 의상 | 수영복 · 전통 문양 수영복 | a swimsuit in a heritage textile pattern with matching trim |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 swimsuit · 드러내기 high-cut leg, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | chin_table · out |  |

옷 종류 shorts · 드러내기 one-shoulder cut, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 apron · 드러내기 off-shoulder neckline, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit
