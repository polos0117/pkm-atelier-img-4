# 푸크린 (0040 · Wigglytuff) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 11c87ff · 2026-11-09T12:13:43.542Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 40 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 837 | `30516d9b5844` | `푸크린_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1098 | `b10a5989d36d` | `푸크린_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1175 | `f909a960579b` | `푸크린_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1150 | `9eb71459866c` | `푸크린_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1011 | `c7178b87e52e` | `푸크린_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1007 | `8a49baf99316` | `푸크린_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1121 | `cbde1709e707` | `푸크린_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 975 | `7078976fd47c` | `푸크린_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1037 | `7c677783a18d` | `푸크린_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 푸크린_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1090 | `a20825b66eaa` | `푸크린_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 목장 | a sunny ranch — a weathered wooden fence, hay bales and horses grazing in the distance |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 이집트 리넨 | an Egyptian-inspired look — a sheer pleated linen sheath over an opaque inner slip dress, a broad jewelled collar and gold arm bands |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 불꽃 막대 · 불꽃 막대를 들어 올린다 | holds a lit sparkler up beside her face |

옷 종류 dress + slip · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 홈웨어 · 플리스 상의 + 조거 팬츠 | a soft fleece pullover with relaxed jogger pants |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 미용 브러시 · 동료의 털을 빗는다 | brushes her companion's fur with a grooming brush |

옷 종류 sweater + trousers · 옷 색 라벤더 · 플럼 (lavender and plum) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 deep V neckline, halter neck · 장면 칸 첫머리 action · 직접 입력 scene

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | prop · rail · 수건 · 목에 건 수건 끝을 잡는다 | holds one end of a towel hung around her neck |

옷 종류 robe + slip · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 place · 직접 입력 outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 crop_top + overalls · 옷 색 — · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 light · 직접 입력 outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 불꽃놀이 강변 | a riverside seating area waiting for festival fireworks |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 tank · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | reach · chest_hand |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · full_body · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 place

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 습지 관찰대 | a wooden wetland lookout among tall reeds beside a quiet marsh |
| 역할 | — |  |
| 의상 | 수영복 · 딥 플런지 원피스 | a one-piece swimsuit with a deep plunging V and a secure wide waistband |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 보드게임 라운지 | a cozy board-game lounge with shelves of game boxes and low tables |
| 역할 | — |  |
| 의상 | 동탄룩 · 자동 — 계열 안에서 장면에 맞게 | a body-hugging, curve-tracing going-out outfit in the Korean 'Dongtan look' style |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 knit_top + skirt · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 detail
