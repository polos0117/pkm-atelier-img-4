# 레시라무 (0643 · Reshiram) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 91f03e6 · 2026-11-03T03:35:29.769Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 643 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 423 | `c17a09928b9a` | `레시라무_light_glossy_promo_f.webp` |
| ② | heavy | ① 레시라무_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `625be094ee07` | `레시라무_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 레시라무_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `503c5dbdb91e` | `레시라무_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 레시라무_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `c44157139ef4` | `레시라무_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 레시라무_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `5c14c5b199a8` | `레시라무_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 레시라무_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `18ee89a089dd` | `레시라무_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 레시라무_light_glossy_promo_f.webp | `casual1-prompt.txt` | 748 | `0bf694d350e4` | `레시라무_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 레시라무_light_glossy_promo_f.webp | `casual2-prompt.txt` | 715 | `f0b93e060192` | `레시라무_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 레시라무_light_glossy_promo_f.webp | `casual3-prompt.txt` | 798 | `330da9713040` | `레시라무_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 작은 가게 | a small shop — a bookstore, record store or plant shop — with crowded shelves |
| 역할 | — |  |
| 의상 | 수영복 · 반두 비키니 | a bandeau bikini with a straight strapless top |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 잔·컵 · 잔을 입에 댄다 | brings a cup to her lips |

옷 종류 bikini + crop_top · 드러내기 high-cut leg, side cutouts · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 가면무도회장 | a chandelier ballroom at a masquerade |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | thumbs_up · hip |  |

옷 종류 crop_top + skirt · 드러내기 strapless top, one-shoulder cut · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 사우나 | a wooden sauna and cold plunge with a cooling lounge |
| 역할 | — |  |
| 의상 | 목욕 차림 · 자동 — 계열 안에서 장면에 맞게 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 robe · 드러내기 high thigh slit, mini length · 장면 칸 첫머리 light · 직접 입력 scene, outfit
