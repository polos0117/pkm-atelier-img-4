# 골루그 (0623 · Golurk) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 6fa2278 · 2026-11-02T00:48:39.491Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 623 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 419 | `75f823f653e1` | `골루그_light_glossy_promo_f.webp` |
| ② | heavy | ① 골루그_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `22768f0521e9` | `골루그_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 골루그_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `9101ab17ca43` | `골루그_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 골루그_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `173d4b5eee4a` | `골루그_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 골루그_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `203c8bb1d987` | `골루그_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 골루그_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `6fa52a226eac` | `골루그_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 골루그_light_glossy_promo_f.webp | `casual1-prompt.txt` | 731 | `4227baa26eae` | `골루그_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 골루그_light_glossy_promo_f.webp | `casual2-prompt.txt` | 675 | `a673c97cf002` | `골루그_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 골루그_light_glossy_promo_f.webp | `casual3-prompt.txt` | 721 | `61875c623f7d` | `골루그_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 미래풍 스파 | a futuristic spa of white curves and soft light |
| 역할 | — |  |
| 의상 | 수영복 · 수영복 위 유카타 | swimwear with a light yukata worn open over it |
| 몸 자세 · 구도 | 옆으로 눕기 · full_body · 정면 | lying on her side |
| 손 · 소품 동작 | behind_head · floor_brace |  |

옷 종류 traditional · 드러내기 off-shoulder neckline, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 노트와 펜 · 노트에 쓴다 | writes in a notebook with a pen on the table |

옷 종류 robe + slip · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 | a grand museum hall with marble statues at night |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | shush · out |  |

옷 종류 crop_top + skirt · 드러내기 bare midriff, cropped hem · 장면 칸 첫머리 action · 직접 입력 scene, outfit
