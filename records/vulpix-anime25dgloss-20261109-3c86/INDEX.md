# 식스테일 (0037 · Vulpix) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 bab0bad · 2026-11-08T23:02:09.586Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 37 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 863 | `277dea019eb9` | `식스테일_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1120 | `cf5a692c53f7` | `식스테일_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1140 | `0b13b5abe481` | `식스테일_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1101 | `785c84d4dee0` | `식스테일_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1188 | `782f66b96edc` | `식스테일_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1059 | `798b12ad082d` | `식스테일_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1011 | `2258734af00b` | `식스테일_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1105 | `2c4f3388cb9c` | `식스테일_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 1021 | `f32840570f58` | `식스테일_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 식스테일_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 995 | `ac14364b2a65` | `식스테일_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 | a village market stall piled with fresh berries |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 자동 — 계열 안에서 장면에 맞게 | an evening dress or night-out outfit |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 dress · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, cutout waist · 장면 칸 첫머리 light

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 서식 공간 설계실 | a habitat design studio with shelter scale models and nest materials on a large table |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 cardigan + leggings · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 sweetheart neckline, open back · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 전통 의상 · 모로코 카프탄 | a Moroccan evening caftan — a long embroidered robe with a decorated belt |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 옆모습 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 robe · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 plunging neckline, one-shoulder cut · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 공원 산책길 | a park path lined with trees and benches |
| 역할 | — |  |
| 의상 | 모험가 · 정글 탐험가 | a jungle-explorer look — a khaki shirt knotted under the bust with rolled sleeves, cargo shorts, a canvas utility belt and lace-up boots |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 shirt + shorts · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 place

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 녹음실 | a foley recording booth with microphones and boxes of noisy props |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 sweetheart neckline, cropped hem · 장면 칸 첫머리 light

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 바닷가 산책길 | a rocky coast path with tide pools |
| 역할 | — |  |
| 의상 | 란제리풍 · 보디수트 | a lingerie bodysuit with a scooped neckline, wide straps and lace side panels |
| 몸 자세 · 구도 | 바닥에 앉기 · environmental · 옆모습 | sitting on the ground |
| 손 · 소품 동작 | lap · floor_brace |  |

옷 종류 bodysuit + lingerie_set · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 루프탑 인피니티 풀 | a rooftop infinity pool with the city skyline behind it |
| 역할 | — |  |
| 의상 | 신화 드레이프 · 이집트 리넨 | an Egyptian-inspired look — a sheer pleated linen sheath over an opaque inner slip dress, a broad jewelled collar and gold arm bands |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 수건 · 수건을 안는다 | holds a towel folded against her chest |

옷 종류 dress + slip · 옷 색 옐로 · 머스터드 (butter yellow and mustard) · 상황 바람에 날림 · 드러내기 deep V neckline, side cutouts · 장면 칸 첫머리 action

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 찜질방 | a Korean jjimjilbang hall with heated floors and sleeping mats |
| 역할 | — |  |
| 의상 | 수영복 · 홀터 비키니 | a halter bikini with a neck tie and an underbust band |
| 몸 자세 · 구도 | 서기 · full_body · 3/4 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bikini · 옷 색 스카이 · 네이비 (sky blue and navy) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 detail

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노래방 | a private karaoke room with spinning coloured lights |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 뒤 3/4 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, mini length · 장면 칸 첫머리 action
