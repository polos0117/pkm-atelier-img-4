# 테라키온 (0639 · Terrakion) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 91f03e6 · 2026-11-03T03:35:10.846Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 639 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 425 | `c886197dfb4c` | `테라키온_light_glossy_promo_f.webp` |
| ② | heavy | ① 테라키온_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `a2b7d1e31ace` | `테라키온_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 테라키온_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `7d94b8943e02` | `테라키온_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 테라키온_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `137272b41e1a` | `테라키온_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 테라키온_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `cec64e82fa40` | `테라키온_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 테라키온_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `33f0b3108e51` | `테라키온_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 테라키온_light_glossy_promo_f.webp | `casual1-prompt.txt` | 650 | `380627fd3479` | `테라키온_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 테라키온_light_glossy_promo_f.webp | `casual2-prompt.txt` | 742 | `1c44f72a9fb2` | `테라키온_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 테라키온_light_glossy_promo_f.webp | `casual3-prompt.txt` | 795 | `d9a720726a1d` | `테라키온_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 쇼핑몰 | a shopping mall atrium with a fountain and glass railings |
| 역할 | — |  |
| 의상 | 란제리풍 · 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |
| 몸 자세 · 구도 | 벽에 기대 서기 · full_body · 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 blouse + traditional · 드러내기 side cutouts, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호텔 방 | a hotel suite with a city view and an open suitcase |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 바디수트형 | a daring adult costume version of {costume}, cut as a high-cut bodysuit with sheer thigh-high tights |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · waist_up · 3/4 정면 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | prop · prop · 책 · 탁자 위 책장을 넘긴다 | turns a page of a book lying open on the table |

옷 종류 bodysuit + leggings · 드러내기 strapless top, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야생 관찰 은신처 | a camouflaged field hide at the edge of a meadow, a tripod set inside |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 shirt · 드러내기 mini length, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit
