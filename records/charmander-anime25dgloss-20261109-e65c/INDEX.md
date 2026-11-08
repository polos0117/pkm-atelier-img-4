# 파이리 (0004 · Charmander) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 95e23f8 · 2026-11-08T16:48:08.760Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 4 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 835 | `a4c54180da81` | `파이리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 파이리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1107 | `027e8c8c8855` | `파이리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 파이리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1108 | `711be4713c25` | `파이리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 파이리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1112 | `ef331244a870` | `파이리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 파이리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1138 | `562098b83b72` | `파이리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 파이리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1051 | `69475d89441d` | `파이리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 파이리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1078 | `6df498e21db4` | `파이리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 파이리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 990 | `eb87234217bc` | `파이리_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 엘프 | an elf costume — a leaf-trimmed short dress, a hooded half-cape and pointed ear tips |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 coat + dress · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 평상복 · 터틀넥 + 퀼팅 조끼 + 바지 | a fine knit turtleneck under a quilted vest with straight trousers |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 옆모습 | crouching low on her heels |
| 손 · 소품 동작 | prop · natural · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 trousers + vest · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 tank · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 운동복 · 자동 — 계열 안에서 장면에 맞게 | activewear made for the activity |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 jumpsuit · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, backless · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 uniform · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 체육관·복싱장 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 traditional · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 빨래방 | a coin laundromat late at night, rows of round machine doors |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail
