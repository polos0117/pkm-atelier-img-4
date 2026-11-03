# 볼트로스 (0642 · Thundurus) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 91f03e6 · 2026-11-03T03:35:17.734Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 642 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 538 | `1d4e0274c17a` | `볼트로스_light_glossy_promo_f.webp` |
| ② | heavy | ① 볼트로스_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `71f71193dc75` | `볼트로스_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 볼트로스_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `4c6d35fe1020` | `볼트로스_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 볼트로스_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `61e94a57f651` | `볼트로스_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 볼트로스_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `54b2b56f0732` | `볼트로스_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 볼트로스_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `72136835de55` | `볼트로스_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 볼트로스_light_glossy_promo_f.webp | `casual1-prompt.txt` | 712 | `84301f629b90` | `볼트로스_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 볼트로스_light_glossy_promo_f.webp | `casual2-prompt.txt` | 697 | `758c98b12cb7` | `볼트로스_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 볼트로스_light_glossy_promo_f.webp | `casual3-prompt.txt` | 771 | `ed20176177fc` | `볼트로스_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 작은 가게 | a small shop — a bookstore, record store or plant shop — with crowded shelves |
| 역할 | — |  |
| 의상 | 란제리풍 · 크바야 응용 레이스 | a kebaya-inspired sheer lace top with floral embroidery over a fitted camisole |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 tank · 드러내기 cropped hem, bare midriff · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 가면무도회장 | a chandelier ballroom at a masquerade |
| 역할 | — |  |
| 의상 | 레트로 · 70년대 디스코 | a 1970s lurex halter jumpsuit with flared legs |
| 몸 자세 · 구도 | 의자에 앉기 · environmental · 정면 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 jumpsuit · 드러내기 high thigh slit, plunging neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 파우더룸 | a club powder room with a lit mirror and neon on the tiles |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 미니 드레스형 | a daring adult costume version of {costume}, cut as a fitted strapless mini dress |
| 몸 자세 · 구도 | 걷기 · three_quarter · 뒤 3/4 | walking |
| 손 · 소품 동작 | prop · down · 칵테일 잔 · 잔을 든다 | holds a cocktail glass by the stem at chest height |

옷 종류 dress · 드러내기 high thigh slit, plunging neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
