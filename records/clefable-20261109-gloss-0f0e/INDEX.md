# 픽시 (0036 · Clefable) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 841a81a · 2026-11-09T07:08:14.077Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 36 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 846 | `08fc3212e985` | `픽시_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 픽시_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1142 | `243d5574cb0c` | `픽시_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 픽시_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 996 | `db31e6324d6d` | `픽시_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 픽시_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 991 | `7cd3f85d6ae7` | `픽시_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 픽시_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1042 | `4a4d597e5789` | `픽시_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 픽시_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1101 | `b7198565a35f` | `픽시_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 픽시_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1173 | `13eb70b9108e` | `픽시_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 픽시_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1056 | `c27fb3e3731c` | `픽시_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 픽시_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1070 | `f7102e7c4510` | `픽시_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 픽시_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1069 | `78a423be2ac7` | `픽시_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬센터 로비 | the bright lobby of a Pokémon Center with a reception counter, sofas and potted plants |
| 역할 | — |  |
| 의상 | 동탄룩 · 페스티벌 — 바디체인 + 크롭 + 데님 숏츠 | a music-festival outfit — a crochet crop top with a delicate body chain, frayed denim micro shorts and ankle boots |
| 몸 자세 · 구도 | 걷기 · face_close · 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + shorts · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 시장 | a busy street market of food stalls and strung bulbs |
| 역할 | — |  |
| 의상 | 수영복 · 트라이앵글 비키니 | a triangle bikini with slider cups and tie-side bottoms |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 미래풍 스파 | a futuristic spa of white curves and soft light |
| 역할 | — |  |
| 의상 | 화보 쿠튀르 · 레트로 퓨처 점프수트 | a sleek retro-futurist jumpsuit with vintage trim |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 — · 드러내기 sweetheart neckline, backless · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 정면 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 대회 무대 | a contest or tournament stage under spotlights |
| 역할 | — |  |
| 의상 | 란제리풍 · 벨벳 세트 | a deep-coloured velvet bralette and high-waisted bottoms |
| 몸 자세 · 구도 | 벽에 기대 서기 · three_quarter · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 열매 저장고 | a cool berry storeroom stacked with padded crates |
| 역할 | — |  |
| 의상 | 전통 의상 · 부부 | a flowing West African boubou — a wide floor-length embroidered robe with a matching head wrap |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · face_close · 옆모습 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 롤러장 | a roller rink under coloured lights |
| 역할 | — |  |
| 의상 | 레트로 · 자동 — 계열 안에서 장면에 맞게 | a period look from a past decade |
| 몸 자세 · 구도 | 옆으로 눕기 · chest_up · 정면 | lying on her side |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 — · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · waist_up · 옆모습 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 vest · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 길가 노점 | a small roadside stall with a counter, a juice pitcher and steaming pots |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · full_body · 3/4 정면 | standing at a waist-high railing or sill, leaning lightly on it |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 반쯤 푼 차림 · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 action · 직접 입력 scene, outfit
