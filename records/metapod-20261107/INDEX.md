# 단데기 (0011 · Metapod) — 지시문 묶음

화풍 `anime_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 10661ba · 2026-11-07T05:45:11.130Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 11 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 599 | `e0d0b1a2e2e1` | `단데기_light_anime_gloss_f.webp` |
| ② | casual1 | ① 단데기_light_anime_gloss_f.webp | `casual1-prompt.txt` | 873 | `3ed3287e0ec1` | `단데기_anime_gloss_f_casual1.webp` |
| ③ | casual2 | ① 단데기_light_anime_gloss_f.webp | `casual2-prompt.txt` | 858 | `923c2ae0f5d6` | `단데기_anime_gloss_f_casual2.webp` |
| ④ | casual3 | ① 단데기_light_anime_gloss_f.webp | `casual3-prompt.txt` | 937 | `f306d4fb23b1` | `단데기_anime_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 단데기_light_anime_gloss_f.webp | `casual4-prompt.txt` | 902 | `5012e024551d` | `단데기_anime_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 단데기_light_anime_gloss_f.webp | `casual5-prompt.txt` | 955 | `1103b2e51383` | `단데기_anime_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 단데기_light_anime_gloss_f.webp | `casual6-prompt.txt` | 844 | `4adf3d067052` | `단데기_anime_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 단데기_light_anime_gloss_f.webp | `casual7-prompt.txt` | 867 | `ffd091cab717` | `단데기_anime_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 dress · 드러내기 halter neck, plunging neckline · 장면 칸 첫머리 place · 직접 입력 scene

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 평상복 · 홀터 탑 + 짧은 반바지 | a halter top and short shorts |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 물병 · 물병을 든다 | holds a water bottle at chest height |

옷 종류 shorts · 드러내기 bare midriff, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 동전 · 동전을 들어 보인다 | holds a single coin up between two fingers |

옷 종류 leggings + sweater · 드러내기 cropped hem, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 울타리 친 풀밭 마당 | an enclosed grassy courtyard with a low wooden fence |
| 역할 | — |  |
| 의상 | 평상복 · 작업 셔츠 + 청바지 | a work shirt with rolled sleeves and jeans |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 shirt + trousers · 드러내기 strapless top, mini length · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 란제리풍 · 비대칭 세트 | an asymmetric lingerie set with one shoulder strap and a diagonal neckline |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 lingerie_set · 드러내기 high-cut leg, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 apron · 드러내기 one-shoulder cut, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | — |  |
| 의상 | 수영복 · 랩 프론트 | a wrap-front swimsuit with a crossed bodice tied at the waist |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 몬스터볼 · 몬스터볼을 천으로 닦는다 | polishes a Poké Ball with a soft cloth |

옷 종류 swimsuit · 드러내기 halter neck, plunging neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
