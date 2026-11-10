# 캐이시 (0063 · Abra) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 9891b4f · 2026-11-10T04:23:39.817Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 63 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 901 | `4b2c6fd73d96` | `캐이시_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1189 | `dbb70abc6471` | `캐이시_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1143 | `0e42293b406a` | `캐이시_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1077 | `461228687bd4` | `캐이시_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1142 | `9398ba884651` | `캐이시_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1143 | `dbb79a78a3e0` | `캐이시_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1136 | `950bbcb8557b` | `캐이시_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1075 | `12a3e691b82c` | `캐이시_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1124 | `20a28dd02778` | `캐이시_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 캐이시_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1080 | `a82e6e48b479` | `캐이시_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | hip · hair_tuck |  |

옷 종류 cardigan + leggings · 옷 색 레드 · 와인 (deep red and wine) · 상황 바람에 날림 · 드러내기 plunging neckline, open back · 장면 칸 첫머리 action · 직접 입력 scene

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 해골 | a skeleton costume — a black stretch catsuit printed with white bones, worn with a red-rose flower crown |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 오락기 조작대 · 오락기를 조작한다 | plays at the control panel of the arcade cabinet in front of her |

옷 종류 bodysuit · 옷 색 — · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 마트·편의점 | a neighbourhood grocery or convenience store with bright aisles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 dress · 옷 색 — · 드러내기 deep V neckline, backless · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온천 마을 족욕 | a hot-spring town footbath under a wooden roof |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 trousers · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬센터 케어실 | a clean Pokémon Center care room with an examination mat, folded blankets and care trays |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 bikini · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | strap · out |  |

옷 종류 tank · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 육상 트랙 | a running track with lane lines and a grandstand |
| 역할 | — |  |
| 의상 | 직업복 · 글래머 레인저룩 | a fitted ranger shirt knotted at the waist over high-waisted utility shorts and lace-up boots |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 수건 · 수건을 안는다 | holds a towel folded against her chest |

옷 종류 shirt + shorts · 옷 색 — · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 place · 직접 입력 outfit
