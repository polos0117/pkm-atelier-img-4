# 니드킹 (0034 · Nidoking) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 d2b2867 · 2026-11-09T12:26:40.228Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 34 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 867 | `20df8e16730d` | `니드킹_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1080 | `0c16a6604b6f` | `니드킹_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1050 | `a03c752b3aa0` | `니드킹_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1163 | `bebb343c4dee` | `니드킹_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1063 | `645dafae6636` | `니드킹_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1106 | `d93aff6035e4` | `니드킹_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1116 | `7968a8f27e97` | `니드킹_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1152 | `ab1fd17a61bf` | `니드킹_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1129 | `7d0acb3fb0a7` | `니드킹_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 니드킹_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 976 | `60c7267c67b5` | `니드킹_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 해변 | a sunny beach with wet sand and shallow surf |
| 역할 | — |  |
| 의상 | 서브컬처 · 그런지 | grunge — an oversized plaid flannel tied at the waist over a slip dress and combat boots |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 비치볼 · 비치볼을 두 손으로 든다 | holds a striped beach ball in both hands in front of her |

옷 종류 — · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 —

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 걷기 · chest_up · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress + slip · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 레인저 초소 | a mountain-trail Pokémon ranger station with rescue gear on the wall |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 턱시도 재킷 + 캐미솔 + 정장 바지 | a sharp tuxedo jacket over a silk camisole with tailored trousers |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 잔·컵 · 잔을 입에 댄다 | brings a cup to her lips |

옷 종류 — · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 —

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온천 마을 족욕 | a hot-spring town footbath under a wooden roof |
| 역할 | — |  |
| 의상 | 수영복 · 컷아웃 원피스 | a fully lined one-piece swimsuit with large cut-outs at the sides of the waist |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 — · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 —

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 전통 의상 · 모로코 카프탄 | a Moroccan evening caftan — a long embroidered robe with a decorated belt |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 robe · 옷 색 — · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 —

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 의자에 앉기 · chest_up · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 — · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 —

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 역할 | — |  |
| 의상 | 평상복 · 물감 묻은 셔츠 | a paint-splattered oversized shirt over shorts |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 국자 · 국자로 카레를 젓는다 | stirs a pot of berry curry with a ladle |

옷 종류 shirt + shorts · 옷 색 — · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 —

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 이집트 리넨 | an Egyptian-inspired look — a sheer pleated linen sheath over an opaque inner slip dress, a broad jewelled collar and gold arm bands |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 — · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 —

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 옆모습 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 — · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 —
