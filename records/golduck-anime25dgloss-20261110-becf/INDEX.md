# 골덕 (0055 · Golduck) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 9b97935 · 2026-11-09T15:51:48.272Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 55 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 907 | `381cec1fa6a3` | `골덕_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 골덕_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1095 | `35a0cd3cabcf` | `골덕_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 골덕_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1126 | `851c77b79c60` | `골덕_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 골덕_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1023 | `05f12ecb87f3` | `골덕_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 골덕_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1050 | `9939ea5e1c01` | `골덕_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 골덕_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1066 | `763bec6e8108` | `골덕_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 골덕_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1047 | `b7afe899b13e` | `골덕_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 골덕_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1068 | `abd67910cf7a` | `골덕_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 골덕_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1087 | `4045a0b283d5` | `골덕_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 골덕_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1019 | `46ace6da34d6` | `골덕_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 작은 가게 | a small shop — a bookstore, record store or plant shop — with crowded shelves |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 bikini · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 스파 라운지 | a quiet spa lounge of robes, herbal tea and dim lamps |
| 역할 | — |  |
| 의상 | 서브컬처 · 펑크 | punk — a studded leather jacket over a ripped plain tee, a tartan mini skirt and combat boots |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 잔·컵 · 잔을 내려놓는다 | sets a cup down on the surface in front of her |

옷 종류 jacket + skirt · 옷 색 — · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 서커스 천막 | a circus tent ring under a striped canopy |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · full_body · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 축제 거리 | a festival street of lanterns, food stalls and paper decorations |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 걷기 · chest_up · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 시스루 유령 | a sheer ghost costume — layers of translucent white chiffon draped over a short white satin slip |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 옆모습 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 slip · 옷 색 아이보리 · 크림 (ivory and warm cream) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 deep V neckline, backless · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 | a village market stall piled with fresh berries |
| 역할 | — |  |
| 의상 | 모험가 · 보물 사냥꾼 | a treasure-hunter look — a fitted tank top, a leather strap harness with small pouches, slim cargo pants and fingerless gloves |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · three_quarter · 3/4 정면 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank + trousers · 옷 색 — · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 폭포 웅덩이 | a rocky waterfall pool under green trees |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 토가 미니 | a modern toga mini dress — one-shoulder draped jersey in a short wrap, a gold cuff on the upper arm and strappy sandals |
| 몸 자세 · 구도 | 무릎 꿇기 · waist_up · 뒤 3/4 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 걷기 · face_close · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress + robe · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 숲길 조사지 | a forest trail edge with a marked trail post, used for wild Pokémon field surveys |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 걷기 · full_body · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + shirt · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 action
