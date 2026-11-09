# 디그다 (0050 · Diglett) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 b55a550 · 2026-11-09T14:15:25.495Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 50 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 849 | `093df447d101` | `디그다_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 디그다_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1065 | `c66a4d0901f1` | `디그다_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 디그다_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1060 | `dfa3d15e250a` | `디그다_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 디그다_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1073 | `2ec1ff25c189` | `디그다_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 디그다_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1035 | `9e7b40339737` | `디그다_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 디그다_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1227 | `a1b88fd9500e` | `디그다_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 디그다_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1110 | `94ad6a7f7f42` | `디그다_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 디그다_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 987 | `2580a303d22d` | `디그다_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 디그다_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1074 | `a0c5409191a9` | `디그다_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 디그다_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 944 | `56de94663a0d` | `디그다_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 레트로 다이너 · 거리·도시 | a retro American diner — a chrome counter, vinyl booths, a jukebox and neon signs in the window |
| 하는 일 | 창밖 비 구경 · 앉기 | watching rain run down the window from an armchair, mug in hand |
| 의상 계열 | 역할극·직업 의상 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 옷 | 의전 교관 | a ceremonial instructor costume with a belted jacket, gloves and a decorative sash |

옷 종류 jacket · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ③ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 · 동료 포켓몬과 함께 | a quiet garden with a feeding bowl set on the grass |
| 하는 일 | 간식 건네기 · 무릎·쪼그림 | offering a small berry treat to her Pokémon companion beside a feeding bowl |
| 의상 계열 | 홈웨어 | soft homewear or loungewear |
| 옷 | 오프숄더 니트 | an off-shoulder knit top slipping from one shoulder over shorts |

옷 종류 knit_top + shorts · 옷 색 — · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ④ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 레드카펫·시상식 · 무대·행사 | a red carpet and award hall with camera flashes |
| 하는 일 | 구두 벗고 쉬기 · 앉기 | sitting down after the night out, heels in one hand |
| 의상 계열 | 저녁 드레스 | an evening dress or night-out outfit |
| 옷 | 슬립 위 실크 로브 | a silk robe over an evening slip |

옷 종류 robe + slip · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 호텔 방 · 저녁 자리 | a hotel suite with a city view and an open suitcase |
| 하는 일 | 소파에 기대 쉬기 · 눕기·기대 눕기 | lounging back on a sofa or daybed, completely at ease |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |

옷 종류 tank · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 사막 오아시스 · 환상 무대 | a desert oasis at golden hour — date palms, a still turquoise pool and silk tents on the dunes |
| 하는 일 | 천천히 거닐기 · 걷기 | strolling through the place at an easy pace |
| 의상 계열 | 모험가 | an adventurer's outfit — a rugged ranch, explorer or pirate look, practical pieces worn short and fitted |
| 옷 | 사파리 원피스 | a safari look — a belted khaki shirt dress with a short hem, a wide-brim hat and tall lace-up boots |

옷 종류 dress + shirt · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, backless · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 체육관·복싱장 · 운동 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 하는 일 | 펜싱 자세 · 움직임 | stepping into an en garde stance, the mask tucked under one arm |
| 의상 계열 | 운동복 | activewear made for the activity |
| 옷 | 스키웨어 — 몸에 붙는 스키 수트 | a sleek fitted one-piece ski suit with goggles pushed up on her head |

옷 종류 swimsuit · 옷 색 — · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑧ casual7 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 수영장 · 물가 | an outdoor pool with lounge chairs and clear blue water |
| 하는 일 | 선베드에 눕기 · 눕기·기대 눕기 | lying back on a sunbed with a cold drink beside her |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |

옷 종류 jumpsuit · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 place

## ⑨ casual8 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 · 오락실·사진 부스 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 하는 일 | 인형 뽑기 · 서기 | bending toward a claw machine, palm on the glass, a plain plush inside |
| 의상 계열 | 포켓몬 코스튬 | a daring adult costume version of {costume} |
| 옷 | 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |

옷 종류 dress · 옷 색 — · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 하맘 · 목욕·스파 | a domed marble hammam with warm stone slabs and brass bowls |
| 하는 일 | 팩 하고 쉬기 · 눕기·기대 눕기 | resting with a clay mask on her face |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |

옷 종류 bikini · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place
