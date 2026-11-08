# 단데기 (0011 · Metapod) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 48b7874 · 2026-11-08T17:46:06.437Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 11 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 817 | `e850352c102e` | `단데기_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 단데기_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1213 | `da910f84641d` | `단데기_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 단데기_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1077 | `1ca4bf0205eb` | `단데기_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 단데기_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1020 | `9665cc6d9bda` | `단데기_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 단데기_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1032 | `95595f524cd0` | `단데기_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 단데기_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1105 | `4de212066903` | `단데기_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 단데기_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1073 | `605f50ba0db5` | `단데기_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 단데기_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1120 | `995bd92e8dad` | `단데기_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 전통 의상 · 모로코 카프탄 | a Moroccan evening caftan — a long embroidered robe with a decorated belt |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 robe · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 레트로 퓨처 집 | a retro-futurist home of rounded chrome appliances and soft panels |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 정면 | lying on her side |
| 손 · 소품 동작 | behind_head · floor_brace |  |

옷 종류 uniform · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 기타 · 기타를 든다 | carries an acoustic guitar by its neck at her side |

옷 종류 bikini · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, bare midriff · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 place · 직접 입력 scene

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 마녀 | a dark witch costume — a plunging black velvet bodysuit under a sheer black chiffon cape, a crooked wide-brimmed pointed hat and sheer thigh-high stockings |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 bodysuit + coat · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 양궁장 | an archery range of targets on a green field |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 lingerie_set + shirt · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 robe + slip · 옷 색 민트 · 틸 (mint and teal) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit
