# 닥트리오 (0051 · Dugtrio) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 b55a550 · 2026-11-09T14:45:42.274Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 51 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 856 | `ffbc8bca76f8` | `닥트리오_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1118 | `b2fb1521aa2a` | `닥트리오_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1026 | `2463b6eaa6bf` | `닥트리오_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1139 | `7bb09f1d0e5d` | `닥트리오_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1084 | `2f1454201b26` | `닥트리오_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1154 | `0c138189190c` | `닥트리오_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1134 | `64e38f0bfdcd` | `닥트리오_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1118 | `be56977c178b` | `닥트리오_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1044 | `18bb512ee955` | `닥트리오_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 닥트리오_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1079 | `4e21eab1ed9c` | `닥트리오_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 목욕 차림 · 목욕 유카타 | a light cotton bath yukata with a soft sash |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 traditional · 옷 색 — · 드러내기 deep V neckline, cropped hem · 장면 칸 첫머리 light · 직접 입력 outfit

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 저녁 사무실 | a modern glass-walled office at dusk — a desk with a monitor, a swivel chair and city lights beyond the window |
| 역할 | — |  |
| 의상 | 수영복 · 반두 비키니 | a bandeau bikini with a straight strapless top |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 우산 · 우산을 쓴다 | holds an umbrella open over her shoulder |

옷 종류 bikini + crop_top · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 코스프레 행사 | a convention photo zone under ring lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 가면 · 가면을 든다 | holds a masquerade mask on a stick up to her eyes |

옷 종류 uniform · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 화보 스튜디오 | an editorial photo studio with a seamless backdrop and dramatic lights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · prop · 카메라 · 찍은 사진을 확인한다 | checks the photo on the back screen of a camera at chest height |

옷 종류 lingerie_set + skirt · 옷 색 — · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 detail

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 안내소 | a Pokémon travel center with a visitor desk, route maps and lodging brochures |
| 역할 | — |  |
| 의상 | 란제리풍 · 보디수트 | a lingerie bodysuit with a scooped neckline, wide straps and lace side panels |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · waist_up · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | prop · prop · 몬스터볼 · 몬스터볼을 천으로 닦는다 | polishes a Poké Ball with a soft cloth |

옷 종류 bodysuit + lingerie_set · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 place

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 의상 수선실 | a sewing and alteration room with a cutting table, a dress form and rolls of fabric |
| 역할 | — |  |
| 의상 | 할로윈 코스튬 · 마녀 | a dark witch costume — a plunging black velvet bodysuit under a sheer black chiffon cape, a crooked wide-brimmed pointed hat and sheer thigh-high stockings |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 휴대폰 · 셀카를 찍는다 | holds a smartphone up at arm's length to take a selfie |

옷 종류 bodysuit + coat · 옷 색 블랙 · 차콜 (black with charcoal accents) · 상황 흘러내린 어깨끈 · 드러내기 sweetheart neckline, off-shoulder neckline · 장면 칸 첫머리 action

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 | a covered porch on a rainy day, umbrellas resting by the door |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 인어 쇼 | a mermaid show costume — a scale-sequined bodice and a flowing chiffon wrap skirt |
| 몸 자세 · 구도 | 쪼그려 앉기 · full_body · 정면 | crouching low on her heels |
| 손 · 소품 동작 | prop · lap · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 skirt · 옷 색 라벤더 · 플럼 (lavender and plum) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 아라비안 나이트 | an Arabian-nights look — a jewelled cropped top, a sheer veil scarf over the shoulders, low-slung flowing chiffon trousers and gold coin anklets |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 수건 · 수건을 안는다 | holds a towel folded against her chest |

옷 종류 crop_top + trousers · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, cutout waist · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 동탄룩 · 클럽 — 메탈릭 슬립 미니 | a club outfit — a liquid-metallic cowl-neck slip mini dress with thin straps and strappy heels |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 옆모습 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | prop · prop · 2단 도시락 · 도시락에 주먹밥을 담는다 | packs rice balls into a two-tier lunchbox |

옷 종류 dress + slip · 옷 색 — · 드러내기 sweetheart neckline, high thigh slit · 장면 칸 첫머리 detail · 직접 입력 outfit
