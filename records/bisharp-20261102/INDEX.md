# 절각참 (0625 · Bisharp) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 633b3f8 · 2026-11-02T01:52:04.299Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 625 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 410 | `51eeb38acc53` | `절각참_light_glossy_promo_f.webp` |
| ② | heavy | ① 절각참_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `7b3a04ba2485` | `절각참_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 절각참_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `a6f647f9ee4b` | `절각참_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 절각참_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `3bdcbcf2b419` | `절각참_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 절각참_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `1a7af592b6f2` | `절각참_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 절각참_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `e0cd5d9de6f3` | `절각참_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 절각참_light_glossy_promo_f.webp | `casual1-prompt.txt` | 805 | `eeb0a1901895` | `절각참_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 절각참_light_glossy_promo_f.webp | `casual2-prompt.txt` | 767 | `6ce98f0550b9` | `절각참_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 절각참_light_glossy_promo_f.webp | `casual3-prompt.txt` | 724 | `5ff7603d8ef8` | `절각참_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 | a village market stall piled with fresh berries |
| 역할 | — |  |
| 의상 | 전통 의상 · 자동 — 계열 안에서 장면에 맞게 | a traditional dress that suits her, worn naturally |
| 몸 자세 · 구도 | 서기 · chest_up · 옆모습 | standing |
| 손 · 소품 동작 | prop · out · 몬스터볼 · 몬스터볼을 얼굴 옆에 든다 | raises a Poké Ball beside her face |

옷 종류 blouse · 드러내기 bare midriff, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 기타 · 기타를 든다 | carries an acoustic guitar by its neck at her side |

옷 종류 bodysuit + leggings · 드러내기 strapless top, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 밤 천문대 | a night observatory under an open dome |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 로데오 카우걸 | a rodeo cowgirl costume — a fringed cropped vest, a western hat, short denim and cowboy boots |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · prop · 책 · 탁자 위 책장을 넘긴다 | turns a page of a book lying open on the table |

옷 종류 vest · 드러내기 cropped hem, open back · 장면 칸 첫머리 action · 직접 입력 scene, outfit
