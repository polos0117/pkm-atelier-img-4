# 자망칼 (0624 · Pawniard) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 633b3f8 · 2026-11-02T01:52:04.180Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 624 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 392 | `2d99e734bdd0` | `자망칼_light_glossy_promo_f.webp` |
| ② | heavy | ① 자망칼_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `1cf42412767a` | `자망칼_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 자망칼_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `1f1e5e5c7669` | `자망칼_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 자망칼_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `ca8f5450d243` | `자망칼_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 자망칼_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `6c3f295a3ebd` | `자망칼_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 자망칼_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `6f17d3894feb` | `자망칼_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 자망칼_light_glossy_promo_f.webp | `casual1-prompt.txt` | 716 | `3463d8868c07` | `자망칼_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 자망칼_light_glossy_promo_f.webp | `casual2-prompt.txt` | 737 | `f323c70bbdae` | `자망칼_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 자망칼_light_glossy_promo_f.webp | `casual3-prompt.txt` | 685 | `d84ba6b6cf4c` | `자망칼_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 댄스 무대 | a lit dance stage or milonga floor |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 lingerie_set + skirt · 드러내기 high-cut leg, side cutouts · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 밤 천문대 | a night observatory under an open dome |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | strap · out |  |

옷 종류 tank · 드러내기 one-shoulder cut, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 작업대에 몸 숙이기 · environmental · 뒤 3/4 | standing at a work surface, upper body leaning slightly forward over it, hips back and weight on both feet |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 jumpsuit · 드러내기 mini length, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit
