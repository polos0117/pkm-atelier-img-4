# 아보크 (0024 · Arbok) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 106d730 · 2026-11-08T23:48:53.486Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 24 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 852 | `e38e956ffbf2` | `아보크_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 아보크_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1014 | `2a901aed7242` | `아보크_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 아보크_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1138 | `ec1ab4a578b3` | `아보크_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 아보크_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1097 | `e4b6b368dea3` | `아보크_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 아보크_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1118 | `42823f1c2b78` | `아보크_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 아보크_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1100 | `f8ac4d46eb86` | `아보크_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 아보크_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1067 | `30e9ba013f7d` | `아보크_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 아보크_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1081 | `4747d0c6df4d` | `아보크_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 아보크_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1059 | `1933f43d5c40` | `아보크_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 아보크_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1126 | `4d82cd1f70c1` | `아보크_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온실·식물원 | a glass greenhouse full of plants with a wooden potting bench |
| 역할 | — |  |
| 의상 | 란제리풍 · 브라렛 + 하이웨이스트 | a soft-cup bralette with wide straps and matching high-waisted bottoms |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 꽃다발 · 꽃다발을 든다 | holds a small bouquet at chest height |

옷 종류 crop_top · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, strapless top · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 현관 | the entryway of her home with a shoe bench, coat hooks and a long mirror |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 robe · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, side cutouts · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 별빛 무대 | a stage under a painted night sky of crystal stars |
| 역할 | — |  |
| 의상 | 화보 쿠튀르 · 레트로 퓨처 점프수트 | a sleek retro-futurist jumpsuit with vintage trim |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 jumpsuit · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, backless · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 | a city rooftop with a water tank, string lights and the skyline |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 vest · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 호박 | a pumpkin costume — an orange satin corset with a puffed tulle mini skirt, black-and-orange striped thigh-high stockings and a tiny green stem headband |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 lingerie_set + skirt · 옷 색 블랙 · 차콜 (black with charcoal accents) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 마을 | a small town square of the Pokémon world with a fountain, flower beds and tiled roofs |
| 역할 | — |  |
| 의상 | 평상복 · 롱코트 + 머플러 | a long wool coat and a knitted scarf |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 아이스크림 · 아이스크림을 든다 | holds an ice cream cone at chest height |

옷 종류 coat · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 detail

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 밤 택시 | the back seat of a taxi at night, city lights streaking past |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · natural · 휴대폰 · 휴대폰을 본다 | holds a smartphone at chest height, screen toward her |

옷 종류 bikini · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 place

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 레드카펫·시상식 | a red carpet and award hall with camera flashes |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 후드 원피스형 | a daring adult costume version of {costume}, cut as a short fitted hooded dress with the hood shaped like its head |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 dress · 옷 색 — · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 action

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 체육관·복싱장 | a training gym with a heavy bag, ring ropes, a fencing strip and racks of weights |
| 역할 | — |  |
| 의상 | 직업복 · 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |
| 몸 자세 · 구도 | 서기 · full_body · 옆모습 | standing |
| 손 · 소품 동작 | wave · down |  |

옷 종류 apron + shirt · 옷 색 스카이 · 네이비 (sky blue and navy) · 상황 젖은 옷 — 비 · 물 튐 · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 detail
