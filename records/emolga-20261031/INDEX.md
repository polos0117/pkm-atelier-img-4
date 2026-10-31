# 에몽가 (0587 · Emolga) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 9c32bb3 · 2026-10-31T06:46:55.980Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 587 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 400 | `9f09b08c97d8` | `에몽가_light_glossy_promo_f.webp` |
| ② | heavy | ① 에몽가_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `444de9ba7d18` | `에몽가_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 에몽가_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `d5421198ca2b` | `에몽가_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 에몽가_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `66b3ec914e61` | `에몽가_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 에몽가_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `a6e56399be41` | `에몽가_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 에몽가_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `be065ac9b37a` | `에몽가_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 에몽가_light_glossy_promo_f.webp | `casual1-prompt.txt` | 749 | `03e385cf45a2` | `에몽가_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 에몽가_light_glossy_promo_f.webp | `casual2-prompt.txt` | 847 | `e7aff5e36317` | `에몽가_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 에몽가_light_glossy_promo_f.webp | `casual3-prompt.txt` | 707 | `9caba07b399d` | `에몽가_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 란제리풍 · 나이트 로브 + 란제리 | a lingerie set under an open silk night robe with a tied sash |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 레코드판 · 레코드판을 두 손으로 든다 | holds a vinyl record half out of its sleeve in both hands |

옷 종류 lingerie_set + robe · 드러내기 high-cut leg, bare midriff · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 | a covered porch on a rainy day, umbrellas resting by the door |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · waist_up · 3/4 정면 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | prop · prop · 수건 · 수건으로 머리를 말린다 | dries her hair with a towel |

옷 종류 dress + robe · 드러내기 open back, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 욕실 | a bright bathroom with a mirror, tiles and folded towels |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 걷기 · face_close · 옆모습 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 robe · 드러내기 high thigh slit, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit
