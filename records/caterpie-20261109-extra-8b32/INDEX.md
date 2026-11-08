# 캐터피 (0010 · Caterpie) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bab0bad · 2026-11-08T23:21:55.443Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 10 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 849 | `f6c1111d9a0d` | `캐터피_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1019 | `25076e3055d7` | `캐터피_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1157 | `646825a0eef0` | `캐터피_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1065 | `f09623890c8c` | `캐터피_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1100 | `43c29c6b8119` | `캐터피_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1201 | `e64337fc0939` | `캐터피_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1078 | `72e66e079212` | `캐터피_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1107 | `2089b55f9fdc` | `캐터피_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1080 | `f9223fda4ffc` | `캐터피_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 캐터피_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1128 | `e2aaed80be8e` | `캐터피_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 겨울 산장 테라스 | a snowy mountain-lodge terrace with a wooden railing and benches above a winter valley |
| 역할 | — |  |
| 의상 | 수영복 · 컷아웃 원피스 | a fully lined one-piece swimsuit with large cut-outs at the sides of the waist |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 잔·컵 · 잔을 내려놓는다 | sets a cup down on the surface in front of her |

옷 종류 swimsuit · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 거실 | her living room with a deep sofa, floor cushions and a low table |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 마녀 | a dark witch costume — a plunging black velvet bodysuit under a sheer black chiffon cape, a crooked wide-brimmed pointed hat and sheer thigh-high stockings |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 bodysuit + coat · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 오락기 조작대 · 오락기를 조작한다 | plays at the control panel of the arcade cabinet in front of her |

옷 종류 apron + shirt · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 정비용 점프수트 | a fitted mechanic's work jumpsuit with rolled sleeves and no real logos |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 jumpsuit · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 사막 오아시스 | a desert oasis at golden hour — date palms, a still turquoise pool and silk tents on the dunes |
| 역할 | — |  |
| 의상 | 화보 쿠튀르 · 레트로 퓨처 점프수트 | a sleek retro-futurist jumpsuit with vintage trim |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 등불 · 등불을 든다 | holds a small hand lantern low at her side |

옷 종류 jumpsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 골목 | a narrow city alley with hanging signboards and wet pavement |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 tank · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 스타디움 | the stands of an open-air Pokémon battle stadium above a marked battle court |
| 역할 | — |  |
| 의상 | 목욕 차림 · 스파 가운 | a plush spa robe tied at the waist |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · prop · 카메라 · 찍은 사진을 확인한다 | checks the photo on the back screen of a camera at chest height |

옷 종류 robe · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 공연장 대기실 | a backstage dressing room with a bulb-lit mirror, a vanity table and costume racks |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 skirt + vest · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 action
