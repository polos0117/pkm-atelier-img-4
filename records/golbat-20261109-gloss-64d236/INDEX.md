# 골뱃 (0042 · Golbat) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 11c87ff · 2026-11-09T12:13:43.684Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 42 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 831 | `ecb41e2e6e67` | `골뱃_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1103 | `5383d0531c44` | `골뱃_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 971 | `14fd224f2cce` | `골뱃_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1106 | `9f51be79f488` | `골뱃_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1056 | `ead615c2823f` | `골뱃_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 999 | `63d0af027632` | `골뱃_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1094 | `1a7463ae7af8` | `골뱃_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1058 | `1819ab92a193` | `골뱃_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1007 | `55eff8db560a` | `골뱃_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 골뱃_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1091 | `651f5fec06c0` | `골뱃_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 목장 | a sunny ranch — a weathered wooden fence, hay bales and horses grazing in the distance |
| 역할 | — |  |
| 의상 | 전통 의상 · 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 blouse · 옷 색 — · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 자동 — 계열 안에서 장면에 맞게 | a daring adult costume version of {costume} |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 deep V neckline, backless · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 리조트 카바나 | a resort cabana with a shaded daybed by the water |
| 역할 | — |  |
| 의상 | 모험가 · 비행사 | a vintage aviatrix look — a cropped leather flight jacket over a fitted top, high-waisted jodhpurs, goggles pushed up on her head and tall boots |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 jacket · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 place

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 나무열매 과수원 | a sunny berry orchard of small trees heavy with ripe, colorful berries |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 바닥에 앉기 · full_body · 뒤 3/4 | sitting on the ground |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 dress · 옷 색 레드 · 와인 (deep red and wine) · 상황 바람에 날림 · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 불꽃놀이 강변 | a riverside seating area waiting for festival fireworks |
| 역할 | — |  |
| 의상 | 란제리풍 · 란제리 위 오픈 셔츠 | a tailored oversized shirt worn open over a matching satin lingerie set |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · full_body · 뒤 3/4 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 lingerie_set + shirt · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 수영복 · 크로셰 비키니 | a fully lined crochet-knit bikini in a sunny resort colour |
| 몸 자세 · 구도 | 서기 · waist_up · 뒤 3/4 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 히노키 탕 | a cedar-wood tub by the window of a mountain inn |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 걷기 · face_close · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 shorts + vest · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코트 | an outdoor court for tennis or basketball |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 옆으로 눕기 · three_quarter · 뒤 3/4 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 대리석 목욕궁 | a Roman marble bath hall — columns, mosaic floors and a wide steaming pool lit from high windows |
| 역할 | — |  |
| 의상 | 화보 쿠튀르 · 레트로 퓨처 점프수트 | a sleek retro-futurist jumpsuit with vintage trim |
| 몸 자세 · 구도 | 옆으로 눕기 · chest_up · 정면 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 place · 직접 입력 outfit
