# 쏘드라 (0116 · Horsea) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 fa45ac2 · 2026-11-12T22:41:50.281Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 116 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 875 | `f20bb1bc6f8a` | `쏘드라_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1157 | `b15d42c6c012` | `쏘드라_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1045 | `523f5ad285a6` | `쏘드라_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1130 | `1c3df054642c` | `쏘드라_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1019 | `82aaa9184591` | `쏘드라_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1141 | `1d5d8f374655` | `쏘드라_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1171 | `1e9c3f62fb45` | `쏘드라_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1047 | `67ca689f6da3` | `쏘드라_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1081 | `384abf5a71e5` | `쏘드라_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1104 | `736ad5153941` | `쏘드라_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 쏘드라_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1081 | `8fb3e418c0e7` | `쏘드라_anime_25d_gloss_f_casual10.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 직업복 · 학예사 카디건 | a neat cardigan over slim trousers with white cotton gloves |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 정면 | lying on her side |
| 손 · 소품 동작 | behind_head · floor_brace |  |

옷 종류 cardigan + trousers · 옷 색 아이보리 · 크림 (ivory and warm cream) · 상황 바람에 날림 · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 place · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 운동복 · 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | lap · natural |  |

옷 종류 swimsuit · 옷 색 — · 장면 자유(자유 장면) · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 jumpsuit · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 서커스 천막 | a circus tent ring under a striped canopy |
| 역할 | — |  |
| 의상 | 란제리풍 · 치파오 응용 실크 | a qipao-inspired silk set with a mandarin collar and frog-button closures |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 정면 | kneeling on the ground |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 dress · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 부두 | a harbor ferry dock beside a small village parcel station |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · out |  |

옷 종류 bikini · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 온천 | an outdoor hot spring of a Pokémon-world mountain town, steam over smooth rocks |
| 역할 | — |  |
| 의상 | 평상복 · 자동 — 계열 안에서 장면에 맞게 | everyday clothes that suit the place and activity |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 shirt + shorts · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호숫가 | a lakeside of flat rocks and still water |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 잔·컵 · 잔을 든다 | holds a cup at chest height |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 place

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 홈웨어 · 아침 로브 | a loosely tied robe |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 robe · 옷 색 — · 옷 자유 · 드러내기 deep V neckline, open back · 장면 칸 첫머리 detail · 직접 입력 outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 action

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · waist_up · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 place
