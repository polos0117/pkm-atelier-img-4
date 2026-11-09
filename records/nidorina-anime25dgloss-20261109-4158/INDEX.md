# 니드리나 (0030 · Nidorina) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 1b9351b · 2026-11-09T03:00:06.782Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 30 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 890 | `8af4f979e4d2` | `니드리나_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1137 | `a514c2cab5ee` | `니드리나_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1061 | `f03d6717fbb6` | `니드리나_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1061 | `7b2766abed06` | `니드리나_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1157 | `bbfd1f10e3af` | `니드리나_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1096 | `1e71092be2b9` | `니드리나_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 981 | `2626260e1f17` | `니드리나_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1038 | `4cd58d6f1bac` | `니드리나_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1037 | `934a922337b2` | `니드리나_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 니드리나_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1007 | `8749c6d03446` | `니드리나_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 하맘 | a domed marble hammam with warm stone slabs and brass bowls |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | wave · down |  |

옷 종류 uniform · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 traditional · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 트레이너 숙소 휴게실 | a trainers' lodge lounge at night with a fireplace, a small bar counter and wooden tables |
| 역할 | — |  |
| 의상 | 직업복 · 자동 — 계열 안에서 장면에 맞게 | practical clothing for her Pokémon-world job, readable through its tools |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 blouse + skirt + vest · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · waist_up · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | prop · prop · 레코드판 · 레코드판을 두 손으로 든다 | holds a vinyl record half out of its sleeve in both hands |

옷 종류 dress · 옷 색 — · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 육상 트랙 | a running track with lane lines and a grandstand |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 3/4 정면 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 수족관 | a service walkway of a Water-Pokémon aquarium beside a large habitat tank |
| 역할 | — |  |
| 의상 | 모험가 · 사막 탐험가 | a desert-explorer look — a light linen scarf loose over the shoulders, a cropped linen top, low-slung loose linen trousers and leather sandals |
| 몸 자세 · 구도 | 무릎 꿇기 · full_body · 뒤 3/4 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 trousers · 옷 색 — · 드러내기 deep V neckline, open back · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 극장·오페라 | the grand lobby and staircase of an opera house |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 아라비안 나이트 | an Arabian-nights look — a jewelled cropped top, a sheer veil scarf over the shoulders, low-slung flowing chiffon trousers and gold coin anklets |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + trousers · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 바람에 날림 · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 정글 유적 | overgrown jungle temple ruins — mossy stone steps, hanging vines and shafts of light through the canopy |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 옆모습 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress + robe · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 place · 직접 입력 outfit
