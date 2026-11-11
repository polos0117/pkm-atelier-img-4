# 우츠보트 (0071 · Victreebel) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 e1f0b24 · 2026-11-11T01:11:43.268Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 71 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 926 | `9fa30d7068fd` | `우츠보트_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1127 | `a54deefaa739` | `우츠보트_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1167 | `1adade84caa0` | `우츠보트_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1020 | `1ba7606f53d5` | `우츠보트_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1185 | `8affbf7a6497` | `우츠보트_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1167 | `e34ba9010834` | `우츠보트_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1112 | `8debf3d02088` | `우츠보트_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1049 | `5917f1a2573e` | `우츠보트_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1130 | `80d7a35f21d9` | `우츠보트_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 우츠보트_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1035 | `a0a631720e1e` | `우츠보트_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 서브컬처 · 고딕 로리타 | gothic lolita — a black-and-white lace jumper skirt with a bonnet |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 skirt + sweater · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 모험가 · 프린지 조끼 | a ranch look — a fringed suede vest over a cropped tank top, low-rise flared jeans and ankle boots |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 tank + trousers + vest · 옷 색 — · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 action · 직접 입력 outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 공원 산책길 | a park path lined with trees and benches |
| 역할 | — |  |
| 의상 | 목욕 차림 · 스파 가운 | a plush spa robe tied at the waist |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 카메라 · 찍은 사진을 확인한다 | checks the photo on the back screen of a camera at chest height |

옷 종류 robe · 옷 색 민트 · 틸 (mint and teal) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 사막 오아시스 | a desert oasis at golden hour — date palms, a still turquoise pool and silk tents on the dunes |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 기대 눕기 · waist_up · 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코트 | an outdoor court for tennis or basketball |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 농구공 · 손가락 끝에서 공을 돌린다 | spins a basketball on one raised fingertip |

옷 종류 swimsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 웨딩 · 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 수건 · 목에 건 수건 끝을 잡는다 | holds one end of a towel hung around her neck |

옷 종류 dress + slip · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 traditional · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 란제리풍 · 벨벳 세트 | a deep-coloured velvet bralette and high-waisted bottoms |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 crop_top · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action
