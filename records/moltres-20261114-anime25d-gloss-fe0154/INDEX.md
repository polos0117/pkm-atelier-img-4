# 파이어 (0146 · Moltres) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 1fcc9ac · 2026-11-14T06:54:11.594Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**① → 멈춤 → 일상컷**(2026-11-11 삼국지 · 원소와 같이). ① 은 **네 장**(첨부 없이 한 장씩) — **두 장은 우리 설계 `light-prompt.txt` 그대로, 두 장은 임의 설계 `light-free.txt`**(설계 주문 — 화풍 · 색 · 머리색 · 체형 · 장갑 폼 · 원작 특징 · 노출 · 구도 · 자세는 우리 것, 큰 실루엣은 목록에서 하나 + 원작에서 딴 제 아이디어 하나, 얼굴 · 눈색(우리 것이든 제 것이든) · 헤어스타일 · 화장 · 표정 · 장면(배경) · 타입 효과는 맡은 쪽이 지어 제 지시문을 쓴다, 둘째 장은 첫째와 확실히 다르게(자세는 같게)). 네 장을 「우리 설계 1 · 2 / GPT 설계 1 · 2」 로 붙여 보이고 **멈추고 묻는다** — 고르기 전엔 일상컷으로 넘어가지 않고 ① 도 올리지 않는다. 고른 장만 올리고 그 장을 붙여 일상컷을 그린다. 임의 설계 장이면 기록 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`)을 남긴다.

**일상컷 옷 자유 컷 두 장** — 계획에 「옷 자유」 로 적힌 컷 가운데 「장면 자유」 가 아닌 한 장은 Outfit 줄이 「노출 의상을 네가 지어라」 다 — 이 묶음의 `outfit-catalog.md`(우리가 쓰는 옷 전부)를 읽고 **거기 없는 옷**을 지어 그 줄에만 써 넣는다(실제로 넘긴 글은 기록에).

**일상컷 자유 장면 두 장**(2026-11-11) — 계획에 「장면 자유」(옷 자유 가운데 한 장) · 「갈래 · 상황 자유」 로 적힌 컷은 SCENE 칸이 설계 주문이다: **장소 · 활동 · 자세 · 구도 · 의상을 맡은 쪽이 짓는다** — 캐릭터의 특징에서 출발해 예상하지 못했지만 자연스럽게 어울리는 일상의 한 순간, 참신함은 장식보다 상황과 행동에서, 이 묶음의 다른 일상컷 · 이 세션에서 그린 컷과 비슷한 장면은 피한다. 장면 자유는 `outfit-catalog.md` 에 **없는 노출 의상**, 갈래 · 상황 자유는 필수 갈래(성인 롤플레이 · 수영복 · 란제리풍) 하나를 골라 **없는 옷** + 끝의 상황 목록에 **없는 노출 상황**. SCENE 밖의 칸(얼굴 · 화풍 · 체형 · 인체 · 옷 갈아입기 · 각도)과 표정 · 노출 강도 · 원작 영향도 줄은 우리 것 그대로 — 그 위에서 제 지시문을 써 그린다. 기록에 `generation.design: "gpt_free"` 와 실제로 넘긴 지시문(`generation.free_prompt`).

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 146 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 966 | `9704ed227f79` | `파이어_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 파이어_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1194 | `8e6561bd7d25` | `파이어_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 파이어_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1284 | `b65e38ca6bed` | `파이어_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 파이어_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1117 | `6913fe9ca764` | `파이어_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 파이어_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1220 | `4b95530e019b` | `파이어_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 파이어_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1061 | `bc8b79fd2054` | `파이어_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 파이어_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1165 | `a039aca9df85` | `파이어_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 파이어_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1161 | `8121a684401a` | `파이어_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 파이어_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1207 | `5e67e2c81f76` | `파이어_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 파이어_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1106 | `4237d482e185` | `파이어_anime_25d_gloss_f_casual9.webp` |
| ⑪ | casual10 | ① 파이어_light_anime_25d_gloss_f.webp | `casual10-prompt.txt` | 1019 | `c399e5421d7b` | `파이어_anime_25d_gloss_f_casual10.webp` |
| ◆ | casual90 | ① 파이어_light_anime_25d_gloss_f.webp | `casual90-prompt.txt` | 1172 | `6e8d721a9ce9` | `파이어_anime_25d_gloss_f_casual90.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 공원 | a city park with benches, old trees and a fountain |
| 역할 | — |  |
| 의상 | 수영복 · 자동 — 계열 안에서 장면에 맞게 | modern swimwear, fully lined and secure during movement |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 선글라스 · 선글라스를 손가락으로 내린다 | lowers a pair of sunglasses down her nose with one finger |

옷 종류 bikini · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 plunging neckline, high-cut leg · 장면 칸 첫머리 detail

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 | a village market stall piled with fresh berries |
| 역할 | — |  |
| 의상 | 모험가 · 해적 코르셋 | a pirate look — a loose shirt open at the neck under a laced leather corset, a long sash at the hip, short breeches and tall cuffed boots |
| 몸 자세 · 구도 | 난간·창턱에 기대 서기 · waist_up · 옆모습 | standing at a waist-high railing or sill |
| 손 · 소품 동작 | prop · rail · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 lingerie_set + shirt · 옷 색 그레이 · 실버 (dove grey and silver) · 상황 소매를 걷고 단추 하나를 풂 · 드러내기 sweetheart neckline, bare midriff · 장면 칸 첫머리 place

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 열매 저장고 | a cool berry storeroom stacked with padded crates |
| 역할 | — |  |
| 의상 | 전통 의상 · 모로코 카프탄 | a Moroccan evening caftan — a long embroidered robe with a decorated belt |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 작은 수납 상자 · 상자를 허리에 안아 든다 | carries a small storage box against her waist |

옷 종류 robe · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 deep V neckline, backless · 장면 칸 첫머리 action

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 평상복 · 멜빵바지 | fitted denim overalls over a cropped top |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · out |  |

옷 종류 crop_top + overalls · 옷 색 — · 갈래 · 상황 자유(자유 장면) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 인어 쇼 | a mermaid show costume — a scale-sequined bodice and a flowing chiffon wrap skirt |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 닦는 천 · 천을 든다 | holds a folded cleaning cloth at chest height |

옷 종류 skirt · 옷 색 — · 옷 자유 · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 detail

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 강가 선착장 | a wooden river dock above calm water |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 이벤트 스태프 | an event staff costume with a fitted vest, name-tag ribbon and lanyard |
| 몸 자세 · 구도 | 걷기 · environmental · 뒤 3/4 | walking |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 vest · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 light

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 서브컬처 · 그런지 | grunge — an oversized plaid flannel tied at the waist over a slip dress and combat boots |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 닦는 천 · 천을 든다 | holds a folded cleaning cloth at chest height |

옷 종류 dress + slip · 옷 색 — · 장면 자유(자유 장면) · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 레트로 · 50년대 홀터 플레이수트 | a 1950s halter playsuit |
| 몸 자세 · 구도 | 의자에 앉기 · face_close · 3/4 정면 | seated on a chair |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 jumpsuit · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 sweetheart neckline, one-shoulder cut · 장면 칸 첫머리 place

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 발코니 | a balcony of her own house in a town of a Pokémon-world town, a balustrade, a small table and the street below |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 tank · 옷 색 세이지 · 올리브 (sage and olive green) · 드러내기 deep V neckline, off-shoulder neckline · 장면 칸 첫머리 light

## ⑪ casual10 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 결혼식장 | a bridal room, garden aisle or reception hall |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 걷기 · environmental · 정면 | walking |
| 손 · 소품 동작 | natural · natural |  |

옷 종류 bodysuit + leggings · 옷 색 — · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 action

## ◆ casual90 — 캐릭터만의 컷(산장 지기 · 노출 bold)

일상 열 장에 더하는 한 장 — 채울 칸이 없다. 막히면 같은 지시문으로 두 번 더(모두 세 번), 그래도 막히면 계획기 `--own --own-level` 로 한 단계 내려 다시 짓는다(IMAGE_RULES 3절 「캐릭터만의 컷」).

| 칸 | 표의 글 |
|---|---|
| 장소 | a mountain hut terrace at dusk — a stone wall, a stacked woodpile, a trail marker post with a rope, a rocky path |
| 장면 | she is a mountain hut keeper glancing back over her shoulder, holding a glowing lantern beside her face to light the trail |
| 의상 | a hut keeper look fitted to her body — a short quilted vest over a fitted sleeveless knit top and short wool shorts with knee socks, bare shoulders and thighs, hiking boots, an orange flame-colored scarf |
| 도구 | a glowing hand lantern (sig_raise) |
| 자세 추천 | lookback_raise |
