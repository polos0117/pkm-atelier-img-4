# 주뱃 (0041 · Zubat) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 42f87ea · 2026-11-09T04:51:47.287Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 41 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 865 | `8a150d6a703e` | `주뱃_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1143 | `3166f9ea336d` | `주뱃_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1174 | `b420eb758d4f` | `주뱃_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1097 | `8eaf3f082048` | `주뱃_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1013 | `54cee97a2fcd` | `주뱃_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1052 | `04fefa5606d6` | `주뱃_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1031 | `e5e4f8a41556` | `주뱃_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1127 | `e1a519ae3d0a` | `주뱃_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1139 | `ed4fd1cf1a54` | `주뱃_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 주뱃_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1082 | `2784143b90c1` | `주뱃_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 수영복 · 반두 비키니 | a bandeau bikini with a straight strapless top |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 수건 · 목에 건 수건 끝을 잡는다 | holds one end of a towel hung around her neck |

옷 종류 bikini + crop_top · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 수영장 | an outdoor pool with lounge chairs and clear blue water |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 챙 넓은 모자 · 쓴 모자 챙을 잡는다 | holds the brim of a wide-brimmed sun hat she wears |

옷 종류 robe · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 란제리풍 · 실크 파자마 세트 | a silk pajama set — a short satin camisole with lace trim and matching tap shorts, the long-sleeved pajama shirt worn open over it |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 기타 · 기타를 친다 | plays an acoustic guitar |

옷 종류 shirt + shorts + tank · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 테마 행사장 | a themed costume event venue with props and a photo wall |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 | a city rooftop party under string lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 가운 + 이브닝 코트 | a long gown under an evening coat |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 coat + dress · 옷 색 — · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야생 관찰 은신처 | a camouflaged field hide at the edge of a meadow, a tripod set inside |
| 역할 | — |  |
| 의상 | 평상복 · 터틀넥 + 퀼팅 조끼 + 바지 | a fine knit turtleneck under a quilted vest with straight trousers |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 trousers + vest · 옷 색 — · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 무릎 꿇기 · full_body · 3/4 정면 | kneeling on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse · 옷 색 레드 · 와인 (deep red and wine) · 상황 흘러내린 어깨끈 · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 | an indoor climbing wall of coloured holds |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 skirt + vest · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 action
