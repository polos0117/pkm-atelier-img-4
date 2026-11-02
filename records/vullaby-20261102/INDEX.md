# 벌차이 (0629 · Vullaby) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 dab49a6 · 2026-11-02T11:42:12.744Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 629 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 407 | `8af1aeeb5b4a` | `벌차이_light_glossy_promo_f.webp` |
| ② | heavy | ① 벌차이_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `2a1f51d86f33` | `벌차이_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 벌차이_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `8b75120dce08` | `벌차이_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 벌차이_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `bd50db445fa9` | `벌차이_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 벌차이_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `1d4903bfd103` | `벌차이_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 벌차이_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `39b21107f8a6` | `벌차이_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 벌차이_light_glossy_promo_f.webp | `casual1-prompt.txt` | 765 | `eccf713a6e2f` | `벌차이_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 벌차이_light_glossy_promo_f.webp | `casual2-prompt.txt` | 686 | `b121cd50436c` | `벌차이_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 벌차이_light_glossy_promo_f.webp | `casual3-prompt.txt` | 757 | `4dfc4aea642d` | `벌차이_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 클럽 | a nightclub with a dance floor under moving coloured lights and a velvet-rope queue at its door |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 lingerie_set + skirt · 드러내기 high-cut leg, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 요정 숲 정원 | a misty enchanted garden of moss, ivy and lanterns |
| 역할 | — |  |
| 의상 | 란제리풍 · 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 옆모습 | kneeling on the ground |
| 손 · 소품 동작 | prop · prop · 꽃다발 · 두 손으로 꽃다발을 든다 | holds a small bouquet in both hands at her waist |

옷 종류 slip · 드러내기 high thigh slit, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 도서관 열람실 | a quiet library reading room with tall bookshelves, reading desks and big windows |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · chest_up · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 traditional · 드러내기 one-shoulder cut, cropped hem · 장면 칸 첫머리 light · 직접 입력 scene, outfit
