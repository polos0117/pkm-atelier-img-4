# 루주라 (0124 · Jynx) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 a3132c6 · 2026-11-13T14:25:15.989Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 124 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 877 | `d7b0e6483e5e` | `루주라_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 루주라_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1156 | `d65055a2292b` | `루주라_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 루주라_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1201 | `8f55b8b2d28d` | `루주라_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 루주라_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1180 | `ba850e514b17` | `루주라_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 루주라_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1161 | `2a54f4d57d6b` | `루주라_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 루주라_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1235 | `52187b6add14` | `루주라_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 루주라_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1107 | `901bd3500966` | `루주라_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 루주라_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1206 | `b0994a15741b` | `루주라_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 루주라_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1237 | `1760d8b50028` | `루주라_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 루주라_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1144 | `b8945ab03576` | `루주라_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 루주라_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1078 | `85240a8fba09` | `루주라_anime_25d_gloss_f_casual10.webp` |
| ◆ | casual90 | ① 루주라_light_anime_25d_gloss_f.webp | `casual90-prompt.txt` | 1088 | `5d1466942d76` | `루주라_anime_25d_gloss_f_casual90.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 의전 교관 | a ceremonial instructor costume with a belted jacket, gloves and a decorative sash |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 카메라 · 카메라를 든다 | carries a camera by its grip at her side |

옷 종류 jacket · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 자동 — 계열 안에서 장면에 맞게 | a stage or fantasy costume |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 동전 · 동전을 들어 보인다 | holds a single coin up between two fingers |

옷 종류 skirt · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 light

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 이집트 리넨 | an Egyptian-inspired look — a sheer pleated linen sheath over an opaque inner slip dress, a broad jewelled collar and gold arm bands |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 dress + slip · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 수영 클럽 장비실 | the equipment room of a swimming club — a slatted bench, racks of kickboards and floats, tiled walls and a high window |
| 역할 | — |  |
| 의상 | 서브컬처 · 자동 — 계열 안에서 장면에 맞게 | a subculture street look |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 crop_top + trousers · 옷 색 — · 장면 자유(자유 장면) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 전통 의상 · 유카타 | a light cotton summer yukata wrapped left over right with a soft obi and geta sandals |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 traditional · 옷 색 — · 옷 자유 · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 action · 직접 입력 outfit

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 수리 가게 작업대 | a small repair kiosk with a cluttered workbench, a low stool, tools hanging on the wall and an open shutter onto the street |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 한쪽 무릎 꿇기 · full_body · 3/4 정면 | kneeling on one knee, the other foot planted flat in front of her |
| 손 · 소품 동작 | prop · floor_brace · 닦는 천 · 천을 든다 | holds a folded cleaning cloth at chest height |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 공방 | a craftsman's workshop of a Pokémon-world town, a heavy workbench, hanging tools and an open door |
| 역할 | — |  |
| 의상 | 모험가 · 해적 코르셋 | a pirate look — a loose shirt open at the neck under a laced leather corset, a long sash at the hip, short breeches and tall cuffed boots |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 lingerie_set + shirt · 옷 색 핑크 · 로즈 (rose pink and blush) · 상황 소매를 걷고 단추 하나를 풂 · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 light

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 패션쇼장 | the front row of a fashion show beside a lit runway |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 가면 · 가면을 든다 | holds a masquerade mask on a stick up to her eyes |

옷 종류 robe + slip · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 수족관 | a service walkway of a Water-Pokémon aquarium beside a large habitat tank |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 옆모습 | sitting on the ground |
| 손 · 소품 동작 | lap · floor_brace |  |

옷 종류 bikini · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 light

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바 | a neon-lit bar counter with backlit bottles |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 tank · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 place

## ◆ casual90 — 캐릭터만의 컷(메이크업 아티스트 · 노출 bold)

일상 열 장에 더하는 한 장 — 채울 칸이 없다. 막히면 같은 지시문으로 두 번 더(모두 세 번), 그래도 막히면 계획기 `--own --own-level` 로 한 단계 내려 다시 짓는다(IMAGE_RULES 3절 「캐릭터만의 컷」).

| 칸 | 표의 글 |
|---|---|
| 장소 | a cosmetics counter — a glass shelf of lipsticks, a lit mirror, a stool and pastel displays |
| 장면 | she is a makeup artist sitting sideways on a stool, loading a lip brush with both hands and a confident smile |
| 의상 | a makeup artist look fitted to her body — a fitted short-sleeved beauty smock tied at the waist and a short skirt, bare legs, a red lip-shaped brooch |
| 도구 | a lip brush (sig_both) |
| 자세 추천 | side_chair_read |
