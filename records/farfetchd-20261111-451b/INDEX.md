# 파오리 (0083 · Farfetch’d) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 e7d9504 · 2026-11-11T14:42:32.578Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 83 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 930 | `a51aa76f90ce` | `파오리_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 파오리_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1215 | `262ecb232037` | `파오리_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 파오리_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1112 | `df97e937f289` | `파오리_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 파오리_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1090 | `032dc983bcb1` | `파오리_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 파오리_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1089 | `fa4daaac8bfb` | `파오리_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 파오리_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1062 | `aeb1fcb8dd5d` | `파오리_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 파오리_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1060 | `16dd9446abc5` | `파오리_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 파오리_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1184 | `fe5700b5e966` | `파오리_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 파오리_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1109 | `74d7c7faa8d1` | `파오리_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 파오리_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1135 | `182bb24a9ddd` | `파오리_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 파오리_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1120 | `e62258be9258` | `파오리_anime_25d_gloss_f_casual10.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 페리 갑판 | the rail of a harbour ferry deck in the wind |
| 역할 | — |  |
| 의상 | 목욕 차림 · 수영복 위 가운 | a spa robe open over a swimsuit |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 robe + swimsuit · 옷 색 — · 옷 자유 · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 light · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 헤드폰 · 헤드폰을 두 손으로 귀에 누른다 | presses over-ear headphones to her ears with both hands |

옷 종류 jacket + skirt · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 해적선 갑판 | the deck of a tall wooden sailing ship at sea — rigging, a ship's wheel, coiled ropes, wooden stairs up to the quarterdeck and billowing sails |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 로데오 카우걸 | a rodeo cowgirl costume — a fringed cropped vest, a western hat, short denim and cowboy boots |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 등불 · 등불을 든다 | holds a small hand lantern low at her side |

옷 종류 vest · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야간 관측소 | a quiet hilltop observatory deck with a telescope under the night sky |
| 역할 | — |  |
| 의상 | 란제리풍 · 브라렛 + 하이웨이스트 | a soft-cup bralette with wide straps and matching high-waisted bottoms |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 내려놓는다 | sets a cup down on the surface in front of her |

옷 종류 crop_top · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 해변 | a sunny beach with wet sand and shallow surf |
| 역할 | — |  |
| 의상 | 홈웨어 · 니트 원피스 | a soft body-hugging knit dress |
| 몸 자세 · 구도 | 기대 눕기 · waist_up · 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 선글라스 · 접은 선글라스를 든다 | holds folded a pair of sunglasses by one arm |

옷 종류 dress · 옷 색 — · 장면 자유(자유 장면) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 역·전철 | a city station platform or the inside of a commuter train |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 헤드폰 · 목에 건 헤드폰을 잡는다 | holds one ear cup of over-ear headphones resting around her neck |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 | a covered porch on a rainy day, umbrellas resting by the door |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 드레스 | a thin-strapped satin slip dress that flows along the body |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 dress + slip · 옷 색 민트 · 틸 (mint and teal) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 light · 직접 입력 scene

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 모험가 · 해적 코르셋 | a pirate look — a loose shirt open at the neck under a laced leather corset, a long sash at the hip, short breeches and tall cuffed boots |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 오락기 조작대 · 오락기를 조작한다 | plays at the control panel of the arcade cabinet in front of her |

옷 종류 lingerie_set + shirt · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 swimsuit · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 detail

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 수건 · 목에 건 수건 끝을 잡는다 | holds one end of a towel hung around her neck |

옷 종류 bikini · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 place
