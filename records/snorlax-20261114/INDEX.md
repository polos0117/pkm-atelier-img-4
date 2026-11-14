# 잠만보 (0143 · Snorlax) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 33887a6 · 2026-11-14T06:01:01.979Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 143 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 919 | `f461bcc2367f` | `잠만보_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1045 | `93efa45759b2` | `잠만보_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1103 | `2178b7dcc510` | `잠만보_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1149 | `3333c3d0094a` | `잠만보_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1193 | `b3065d053f09` | `잠만보_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1255 | `75b0089d019c` | `잠만보_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1138 | `be35412d67d9` | `잠만보_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1097 | `fbcc45adb1aa` | `잠만보_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1203 | `31e16f9e0a0b` | `잠만보_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1330 | `256bbb9d9304` | `잠만보_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1232 | `c081364fae10` | `잠만보_anime_25d_gloss_f_casual10.webp` |
| ◆ | casual90 | ① 잠만보_light_anime_25d_gloss_f.webp | `casual90-prompt.txt` | 1031 | `f7ae770389a3` | `잠만보_anime_25d_gloss_f_casual90.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 무릎 꿇기 · environmental · 뒤 3/4 | kneeling on the ground |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 정글 유적 | overgrown jungle temple ruins — mossy stone steps, hanging vines and shafts of light through the canopy |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 걷기 · environmental · 3/4 정면 | walking |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 bikini · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 deep V neckline, high-cut leg · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 캠프장 | a quiet campsite with a small tent and a cooking kit |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 이집트 리넨 | an Egyptian-inspired look — a sheer pleated linen sheath over an opaque inner slip dress, a broad jewelled collar and gold arm bands |
| 몸 자세 · 구도 | 의자에 앉기 · three_quarter · 정면 | seated on a chair |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 dress + slip · 옷 색 — · 장면 자유(자유 장면) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 공연장 대기실 | a backstage dressing room with a bulb-lit mirror, a vanity table and costume racks |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · chest_up · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 tank · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 cardigan + leggings · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 목욕 차림 · 수영복 위 가운 | a spa robe open over a swimsuit |
| 몸 자세 · 구도 | 엎드리기 · face_close · 정면 | lying on her front |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe + swimsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 작은 가게 | a small shop — a bookstore, record store or plant shop — with crowded shelves |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 걷기 · full_body · 옆모습 | walking |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 uniform · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 펜트하우스 | a penthouse window wall over the city at night |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 기대 눕기 · three_quarter · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 lingerie_set · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 | a covered porch on a rainy day, umbrellas resting by the door |
| 역할 | — |  |
| 의상 | 휴양지 차림 · 린넨 셔츠와 반바지 | an oversized linen shirt half-buttoned over a bralette top with linen shorts |
| 몸 자세 · 구도 | 쪼그려 앉기 · waist_up · 뒤 3/4 | crouching low on her heels |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 crop_top + shirt + shorts · 옷 색 — · 옷 자유 · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 연습실 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 역할 | — |  |
| 의상 | 운동복 · 발레 연습복 — 레오타드 + 랩스커트 | a ballet leotard with a short wrap skirt, tights and leg warmers |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 bodysuit + leggings + skirt · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 action

## ◆ casual90 — 캐릭터만의 컷(도시락 가게 주인 · 노출 bold)

일상 열 장에 더하는 한 장 — 채울 칸이 없다. 막히면 같은 지시문으로 두 번 더(모두 세 번), 그래도 막히면 계획기 `--own --own-level` 로 한 단계 내려 다시 짓는다(IMAGE_RULES 3절 「캐릭터만의 컷」).

| 칸 | 표의 글 |
|---|---|
| 장소 | a lunch box shop — steaming rice cookers, rows of wrapped lunch boxes, a wooden counter with a cutting board, a small eat-in table with stools |
| 장면 | she is the owner of the lunch shop sitting upright at the eat-in table with her ankles crossed, resting a moment before the next rush |
| 의상 | a lunch shop cook look fitted to her body — a white cook's apron over a fitted off-shoulder top and short skirt, bare shoulders and legs, a wide cloth belt tied over the apron |
| 도구 | — |
| 자세 추천 | ankles_sit |
