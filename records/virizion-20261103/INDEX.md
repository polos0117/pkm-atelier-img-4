# 비리디온 (0640 · Virizion) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7958331 · 2026-11-02T21:06:58.862Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 640 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 420 | `90e6b4952d6d` | `비리디온_light_glossy_promo_f.webp` |
| ② | heavy | ① 비리디온_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `baa0565ab8d1` | `비리디온_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 비리디온_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `735c7c334517` | `비리디온_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 비리디온_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 251 | `b170405ad241` | `비리디온_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 비리디온_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 257 | `f23563c0afe2` | `비리디온_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 비리디온_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 250 | `1f537c7ab4db` | `비리디온_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 비리디온_light_glossy_promo_f.webp | `casual1-prompt.txt` | 754 | `e1a81d8261ea` | `비리디온_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 비리디온_light_glossy_promo_f.webp | `casual2-prompt.txt` | 725 | `4c7e1402fc02` | `비리디온_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 비리디온_light_glossy_promo_f.webp | `casual3-prompt.txt` | 837 | `e326664774da` | `비리디온_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 대회 무대 | a contest or tournament stage under spotlights |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 코르셋형 | a daring adult costume version of {costume}, cut as a laced corset bustier with a short flared skirt |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 마이크 · 마이크를 입가에 댄다 | holds a microphone close to her lips |

옷 종류 lingerie_set + skirt · 드러내기 plunging neckline, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 겨울 산장 테라스 | a snowy mountain-lodge terrace with a wooden railing and benches above a winter valley |
| 역할 | — |  |
| 의상 | 수영복 · 랩 프론트 | a wrap-front swimsuit with a crossed bodice tied at the waist |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · natural · 토트백 · 가방끈을 어깨에 걸쳐 잡는다 | holds the strap of a canvas tote bag on her shoulder |

옷 종류 swimsuit · 드러내기 high-cut leg, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 | a shaded lawn with a picnic blanket under a broad tree |
| 역할 | — |  |
| 의상 | 운동복 · 스키 재킷 + 스키 팬츠 | a fitted ski jacket and padded ski pants |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 나무열매 간식 · 동료에게 간식을 내민다 | offers a small berry treat to her companion |

옷 종류 jacket + trousers · 드러내기 cropped hem, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
