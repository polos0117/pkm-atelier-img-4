# 독침붕 (0015 · Beedrill) — 지시문 묶음

화풍 `anime_25d_gloss` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 80ab039 · 2026-11-08T21:16:20.042Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.

**프롬프트 임의 수정 금지 — 이미지 모델에도 똑같다(2026-11-08).** IMAGE_RULES.md 1절의 변경 사유(settings 고친 뒤 build · 막혔을 때 계획기 다시 계획 · 같은 지시문 재생성 · 사용자가 시킨 부분 고치기) 말고는 낱말 하나도 고치지 않는다. image_gen 에도 이 글 그대로 넘기고(`submitted` 0 일 때만) 고쳐 쓰지 말고 그대로 그리게 한다.

**노출은 세션이 줄이지 않는다.** 노출 · 의상 줄을 빼거나 누그러뜨리거나 고정값(강도 strong · 노출 bold)을 미리 낮추지 않는다 — 실제로 막혔을 때만 IMAGE_RULES.md 3절 7 순서(같은 지시문 한 번 → 노출 한 단계씩 settings exposure · exposure_why → 계획기로 장면 다시). 검수 `qa.json` 에 컷마다 `exposure`(match · weaker · stronger + 근거).
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 15 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 889 | `ea20bb731c44` | `독침붕_light_anime_25d_gloss_f.webp` |
| ② | casual1 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual1-prompt.txt` | 1135 | `94279f6e2eb6` | `독침붕_anime_25d_gloss_f_casual1.webp` |
| ③ | casual2 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual2-prompt.txt` | 1146 | `6ad6c94d268e` | `독침붕_anime_25d_gloss_f_casual2.webp` |
| ④ | casual3 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual3-prompt.txt` | 1071 | `8a6acec8445e` | `독침붕_anime_25d_gloss_f_casual3.webp` |
| ⑤ | casual4 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual4-prompt.txt` | 1135 | `0b15272e300f` | `독침붕_anime_25d_gloss_f_casual4.webp` |
| ⑥ | casual5 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual5-prompt.txt` | 1111 | `f36b74eb878a` | `독침붕_anime_25d_gloss_f_casual5.webp` |
| ⑦ | casual6 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual6-prompt.txt` | 1053 | `721652ead3aa` | `독침붕_anime_25d_gloss_f_casual6.webp` |
| ⑧ | casual7 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual7-prompt.txt` | 1138 | `27020f65f541` | `독침붕_anime_25d_gloss_f_casual7.webp` |
| ⑨ | casual8 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual8-prompt.txt` | 998 | `4df82f1d01fb` | `독침붕_anime_25d_gloss_f_casual8.webp` |
| ⑩ | casual9 | ① 독침붕_light_anime_25d_gloss_f.webp | `casual9-prompt.txt` | 1058 | `afe73e00d79b` | `독침붕_anime_25d_gloss_f_casual9.webp` |

## ② casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 연습장 | an outdoor battle practice field marked with cones and chalk lines |
| 역할 | — |  |
| 의상 | 동탄룩 · 튜브탑 + 하이웨이스트 레깅스 | a tight tube top under an open cropped cardigan with glossy high-waisted leggings that outline the hips and legs |
| 몸 자세 · 구도 | 서기 · face_close · 정면 | standing |
| 손 · 소품 동작 | v_sign · out |  |

옷 종류 cardigan + leggings · 옷 색 민트 · 틸 (mint and teal) · 드러내기 deep V neckline, strapless top · 장면 칸 첫머리 place

## ③ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 부엌 | a sunny home kitchen in a Pokémon-world town, bowls of berries on the counter |
| 역할 | — |  |
| 의상 | 모험가 · 사파리 원피스 | a safari look — a belted khaki shirt dress with a short hem, a wide-brim hat and tall lace-up boots |
| 몸 자세 · 구도 | 서기 · waist_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · pocket · 몬스터볼 · 몬스터볼을 든다 | holds a Poké Ball at chest height |

옷 종류 dress + shirt · 옷 색 카멜 · 초콜릿 (camel and chocolate brown) · 드러내기 sweetheart neckline, halter neck · 장면 칸 첫머리 action

## ④ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 | a quiet garden with a feeding bowl set on the grass |
| 역할 | — |  |
| 의상 | 홈웨어 · 오버사이즈 티 + 쇼츠 | an oversized tee and shorts |
| 몸 자세 · 구도 | 무릎 꿇기 · three_quarter · 3/4 정면 | kneeling on the ground |
| 손 · 소품 동작 | pet_companion · natural |  |

옷 종류 shorts · 옷 색 핑크 · 로즈 (rose pink and blush) · 드러내기 plunging neckline, open back · 장면 칸 첫머리 detail

## ⑤ casual4 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 리조트 카바나 | a resort cabana with a shaded daybed by the water |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 슬립 위 실크 로브 | a silk robe over an evening slip |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 robe + slip · 옷 색 그레이 · 실버 (dove grey and silver) · 드러내기 deep V neckline, high thigh slit · 장면 칸 첫머리 light

## ⑥ casual5 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 전망대 | a hilltop lookout over a wide valley |
| 역할 | — |  |
| 의상 | 수영복 · 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |
| 몸 자세 · 구도 | 서기 · waist_up · 정면 | standing |
| 손 · 소품 동작 | clasp_both · clasp_both |  |

옷 종류 bikini · 옷 색 코랄 · 오렌지 (coral and soft orange) · 드러내기 sweetheart neckline, cutout waist · 장면 칸 첫머리 action

## ⑦ casual6 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 베이커리 작업실 | a small bakery workroom with a floury wooden worktable and warm ovens |
| 역할 | — |  |
| 의상 | 포켓몬 코스튬 · 크롭 투피스형 | a daring adult costume version of {costume}, cut as a cropped top and a micro skirt that bare the midriff |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 crop_top + skirt · 옷 색 — · 드러내기 plunging neckline, cropped hem · 장면 칸 첫머리 place

## ⑧ casual7 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 내 방 | her own room in a small house of a Pokémon-world town, a shelf of travel gear by the window |
| 역할 | — |  |
| 의상 | 평상복 · 터틀넥 + 퀼팅 조끼 + 바지 | a fine knit turtleneck under a quilted vest with straight trousers |
| 몸 자세 · 구도 | 앉아 앞으로 기울이기 · three_quarter · 옆모습 | seated, leaning slightly forward toward the table, forearms near its edge |
| 손 · 소품 동작 | prop · prop · 게임 패드 · 게임을 한다 | plays with a game controller in both hands, thumbs on the sticks |

옷 종류 trousers + vest · 옷 색 스카이 · 네이비 (sky blue and navy) · 상황 반쯤 푼 차림 · 드러내기 deep V neckline, mini length · 장면 칸 첫머리 detail

## ⑨ casual8 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 라이브 하우스 | a small live house with a low stage, a crowd barrier and amps |
| 역할 | — |  |
| 의상 | 란제리풍 · 보디수트 | a lingerie bodysuit with a scooped neckline, wide straps and lace side panels |
| 몸 자세 · 구도 | 가장자리에 걸터앉기 · environmental · 3/4 정면 | perched on a ledge or edge |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 bodysuit + lingerie_set · 옷 색 레드 · 와인 (deep red and wine) · 드러내기 sweetheart neckline, high-cut leg · 장면 칸 첫머리 light

## ⑩ casual9 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 노천 온천 | an open-air hot spring among steaming rocks |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |
| 몸 자세 · 구도 | 물에 몸 담그기 · chest_up · 옆모습 | chest-deep in the water |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 apron · 옷 색 아이보리 · 크림 (ivory and warm cream) · 드러내기 plunging neckline, off-shoulder neckline · 장면 칸 첫머리 detail
