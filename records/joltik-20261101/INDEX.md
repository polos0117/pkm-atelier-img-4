# 파쪼옥 (0595 · Joltik) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 1e6e43d · 2026-11-01T04:56:31.612Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 595 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 393 | `22ba919f3963` | `파쪼옥_light_glossy_promo_f.webp` |
| ② | heavy | ① 파쪼옥_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `d9a8b7f65d15` | `파쪼옥_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 파쪼옥_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `ddb74e88c185` | `파쪼옥_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 파쪼옥_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `db0e446973c0` | `파쪼옥_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 파쪼옥_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `1a50b291886b` | `파쪼옥_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 파쪼옥_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `de34a3ab47ef` | `파쪼옥_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 파쪼옥_light_glossy_promo_f.webp | `casual1-prompt.txt` | 717 | `e64b118de040` | `파쪼옥_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 파쪼옥_light_glossy_promo_f.webp | `casual2-prompt.txt` | 750 | `5f74077e5152` | `파쪼옥_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 파쪼옥_light_glossy_promo_f.webp | `casual3-prompt.txt` | 670 | `adaa0882edf6` | `파쪼옥_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 강가 선착장 | a wooden river dock above calm water |
| 역할 | — |  |
| 의상 | 홈웨어 · 원숄더 라운지 | a one-shoulder lounge top and matching soft pants |
| 몸 자세 · 구도 | 서기 · three_quarter · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · prop · 낚싯대 · 낚싯대를 던진다 | casts the line with a fishing rod |

옷 종류 trousers · 드러내기 bare midriff, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 패션쇼장 | the front row of a fashion show beside a lit runway |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 마이크 · 마이크를 입가에 댄다 | holds a microphone close to her lips |

옷 종류 robe + slip · 드러내기 plunging neckline, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 롤러 디스코 | 1970s satin hot pants and a tube top |
| 몸 자세 · 구도 | 걷기 · environmental · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 trousers · 드러내기 one-shoulder cut, strapless top · 장면 칸 첫머리 light · 직접 입력 scene, outfit
