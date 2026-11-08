# 아보 (0023 · Ekans) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 d338021 · 2026-11-08T21:41:48.389Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 23 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 845 | `f56ad8b5e32e` | `아보_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 아보_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1192 | `2c0d72806b80` | `아보_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 아보_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1103 | `ac3af439ca8a` | `아보_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 아보_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1065 | `010cd3e2e16d` | `아보_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 아보_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1068 | `0225424731be` | `아보_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 아보_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1074 | `c09c27244054` | `아보_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 아보_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1131 | `b9013fb05aab` | `아보_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 아보_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1168 | `0a09bcca9594` | `아보_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 아보_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1023 | `d8959becbf32` | `아보_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 아보_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 996 | `4e0b9a91e66c` | `아보_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 폭포 웅덩이 | a rocky waterfall pool under green trees |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 수건 · 목에 건 수건 끝을 잡는다 | holds one end of a towel hung around her neck |

옷 종류 apron + shirt · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 action

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 거대한 서고 | a vast fantasy library of towering shelves, spiral stairs and floating candles |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 등불 · 등불을 들어 비춘다 | lifts a small hand lantern to chest height |

옷 종류 traditional · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 한쪽 어깨 여신 | a one-shoulder goddess gown of flowing chiffon gathered at one shoulder with a gold brooch, the other shoulder and arm bare, a thigh-high slit |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 dress · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 모험가 · 프린지 조끼 | a ranch look — a fringed suede vest over a cropped tank top, low-rise flared jeans and ankle boots |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 게임 패드 · 게임을 한다 | plays with a game controller in both hands, thumbs on the sticks |

옷 종류 tank + trousers + vest · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 마이크 · 마이크를 입가에 댄다 | holds a microphone close to her lips |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 | a covered porch on a rainy day, umbrellas resting by the door |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 미용 브러시 · 동료의 털을 빗는다 | brushes her companion's fur with a grooming brush |

옷 종류 swimsuit · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail · 직접 입력 scene

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 전통 의상 · 부부 | a flowing West African boubou — a wide floor-length embroidered robe with a matching head wrap |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 robe · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 저녁 사무실 | a modern glass-walled office at dusk — a desk with a monitor, a swivel chair and city lights beyond the window |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 레트로 우주비행사 | a retro space-age costume — a fitted white jumpsuit with silver trim and moon boots |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 노트와 펜 · 노트에 쓴다 | writes in a notebook with a pen on the table |

옷 종류 jumpsuit · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 댄스 무대 | a lit dance stage or milonga floor |
| 역할 | — |  |
| 의상 | 란제리풍 · 뷔스티에풍 | a bustier-inspired satin top with a long structured bodice and vertical seams |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 lingerie_set · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 detail
