# 윈디 (0059 · Arcanine) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 59f0988 · 2026-11-09T21:08:50.952Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 59 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 894 | `8b069b97a211` | `윈디_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 윈디_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1188 | `3aac22f65fc0` | `윈디_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 윈디_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1140 | `09d5fe4027a3` | `윈디_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 윈디_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1063 | `13e6dc576ff4` | `윈디_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 윈디_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1047 | `c3946a12e5b2` | `윈디_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 윈디_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1134 | `9a11a83be676` | `윈디_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 윈디_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1147 | `c82ebd66951b` | `윈디_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 윈디_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1079 | `9a81afc2b5de` | `윈디_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 윈디_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1030 | `c7588c0a466c` | `윈디_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 윈디_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1062 | `3d6ae3d69d0d` | `윈디_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 검은 고양이 | a black cat costume — a glossy black strapless bodysuit, sheer black tights, a cat-ear headband, a curling tail and a bell choker |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 bodysuit + leggings · 옷 색 블랙 · 차콜 (black with charcoal accents) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 골목 | a narrow city alley with hanging signboards and wet pavement |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 토트백 · 가방끈을 어깨에 걸쳐 잡는다 | holds the strap of a canvas tote bag on her shoulder |

옷 종류 uniform · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 detail

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 공방 | a tidy Pokémon craft workshop with a padded workbench, fine hand tools and ball shells |
| 역할 | — |  |
| 의상 | 수영복 · 보이쇼트 | a swimsuit set with a fitted top and square-cut boyshort bottoms |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 swimsuit · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공연장 대기실 | a backstage dressing room with a bulb-lit mirror, a vanity table and costume racks |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 아라비안 나이트 | an Arabian-nights look — a jewelled cropped top, a sheer veil scarf over the shoulders, low-slung flowing chiffon trousers and gold coin anklets |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 동전 · 동전을 들어 보인다 | holds a single coin up between two fingers |

옷 종류 crop_top + trousers · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 침실 | her bedroom, an unmade bed and soft window light |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 손거울 · 손거울을 본다 | holds a compact mirror open in front of her face |

옷 종류 lingerie_set · 옷 색 — · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 등불을 띄운 강 | a night river covered with floating paper lanterns, stone steps leading down to the water |
| 역할 | — |  |
| 의상 | 란제리풍 · 실크 파자마 세트 | a silk pajama set — a short satin camisole with lace trim and matching tap shorts, the long-sleeved pajama shirt worn open over it |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 shirt + shorts + tank · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 평상복 · 후디 + 레깅스 | a cropped hoodie and leggings |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 leggings + sweater · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 히노키 탕 | a cedar-wood tub by the window of a mountain inn |
| 역할 | — |  |
| 의상 | 목욕 차림 · 스파 가운 | a plush spa robe tied at the waist |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 robe · 옷 색 — · 드러내기 plunging neckline, backless · 장면 칸 첫머리 detail · 직접 입력 outfit
