# pkm-atelier-img-4

`pkm-atelier` 의 **넷째** 그림 저장소다(2026-10-31 부터 열림). 코드는 [pkm-atelier](https://github.com/polos0117/pkm-atelier),
앞 저장소는 [pkm-atelier-img](https://github.com/polos0117/pkm-atelier-img)(0 번) · [pkm-atelier-img-2](https://github.com/polos0117/pkm-atelier-img-2)(1 번) ·
[pkm-atelier-img-3](https://github.com/polos0117/pkm-atelier-img-3)(2 번) 에 있다.

## 왜 하나 더 두나

GitHub Pages 사이트 한 개는 1 GB 까지다. 셋째 저장소가 약 938 MB 가 되어(2026-10-31 — 썸네일 워크플로의 900 MB 경고)
새 그림은 여기에 올린다. 앞 저장소의 그림은 지우지도 옮기지도 않는다 — 옛 주소가 그대로 산다.

어느 그림이 어느 저장소에 있는지는 등록기가 `pkm-atelier` 의 `data/img.json` 에 `"where": {"<파일>": 3}` 으로 적고,
화면(`lib/img.js` 의 `BASES`)이 그 번호로 주소를 고른다.

## 규칙

- **새 그림은 여기에만 올린다.** 앞 저장소 셋은 닫혔다 — 그쪽에 새 이름이 올라오면 등록이 전부 멈춘다.
  이미 있는 이름을 고쳐 그리는 교체만 그 파일이 있는 저장소에 덮어쓴다.
- 같은 이름을 두 저장소에 두지 않는다(등록이 멈춘다).
- 새 그림은 WebP 품질 85(method 6)로 만든다. 1024×1536 기준 한 장 약 0.3~0.4 MB.
- **생성 원본 PNG 는 올리지 않는다** — 기록(`records/<종>-<날짜>/`)에는 원본의 sha256 과 프롬프트·선택값·QA 만 둔다.
  원본은 그 세션 안에만 있다(pkm-atelier 의 IMAGE_RULES.md "원본 PNG").
- 파일 이름 규칙·자리는 앞 저장소와 같다 — [IMAGE_RULES.md](https://github.com/polos0117/pkm-atelier/blob/main/IMAGE_RULES.md).
- 일상컷 장부(`records/casual-ledger.json`)·세션별 예약(`records/casual-reservations/`)·자동화 상태(`records/automation/state.json`)는
  **둘째 저장소에 그대로** 둔다 — 여러 세션이 한 곳을 보게.

```
img/<파일>.webp        원본. 폼 초상은 1024×1536 (2:3)
img/thumb/<같은 이름>   목록용. 긴 변 512 — 워크플로가 만든다
sprites/<이름>/         도트(img/ 밖 — 등록기·썸네일이 읽지 않는다). pkm-atelier 의 data/sprites.json 에서 인물마다 base 로 가리킨다
records/<종>-<날짜>/    생성 기록(원본 PNG 없이)
```

## 처음 한 번

1. 공개(Public) 저장소로 만든다 — Pages 무료 요금제는 공개 저장소만 낸다.
2. Settings → Pages → Source: Deploy from a branch, `main` / `(root)`.
3. Settings → Secrets and variables → Actions → `CODE_REPO_TOKEN`(Fine-grained token, 저장소 `pkm-atelier` 하나, Contents Read and write).

`.nojekyll` 은 Pages 가 파일을 있는 그대로 내보내게 한다. 워크플로의 "크기" 단계가 900 MB 를 넘으면
경고를 띄운다 — 그때 `pkm-atelier-img-5` 를 같은 방법으로 준비한다.
