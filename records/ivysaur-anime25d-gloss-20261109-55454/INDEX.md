# 이상해풀 (0002 · Ivysaur) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 cdc4ca3 · 2026-11-08T17:17:10.034Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 2 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 873 | `4733628ae02a` | `이상해풀_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 이상해풀_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1127 | `cb0adab6c7d6` | `이상해풀_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 이상해풀_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1032 | `b12741c19a74` | `이상해풀_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 이상해풀_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1121 | `aa1d40d6ce8d` | `이상해풀_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 이상해풀_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1085 | `47474d1ca700` | `이상해풀_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 이상해풀_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1018 | `37e3bbbc631a` | `이상해풀_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 이상해풀_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1000 | `40ae0cabff33` | `이상해풀_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 이상해풀_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1131 | `6e8d8e44c8ee` | `이상해풀_anime_25d_gloss_f_casual7.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬센터 케어실 | a clean Pokémon Center care room with an examination mat, folded blankets and care trays |
| 역할 | — |  |
| 의상 | 홈웨어 · 자동 — 계열 안에서 장면에 맞게 | soft homewear or loungewear |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 shorts + sweater · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, open back · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 발코니 | a small balcony with potted plants, a railing and the city beyond |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 서기 · environmental · 옆모습 | standing |
| 손 · 소품 동작 | prop · prop · 휴대용 게임기 · 휴대용 게임기로 논다 | plays on a handheld game console |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 웨딩 · 브라이덜 레이스 | a white lace bridal lingerie set with a short veil |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 lingerie_set · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 산장 | a mountain lodge with a front counter and a fireplace |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 편지 · 편지를 두 손으로 읽는다 | reads a handwritten letter held in both hands |

옷 종류 dress + robe · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 런웨이 | a fashion runway under white spotlights |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 traditional · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 카페 | a neighbourhood café with a counter and window seats |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 걷기 · full_body · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 tank · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 uniform · 옷 색 민트 · 틸 (mint and teal) · 드러내기 sweetheart neckline, mini length · 장면 칸 첫머리 place
