# 민원서비스 찾기

서비스명 검색 + 민원분야 필터로 민원 서비스 22건을 찾는 정적 웹페이지입니다. 빌드 과정 없이 `index.html` 하나로 동작합니다.

## GitHub Pages 배포
1. GitHub에서 새 저장소를 만듭니다 (예: `minwon-search`, Public).
2. `index.html`, `data.json`, `README.md`를 저장소 루트에 업로드합니다.
3. Settings → Pages → Build and deployment → Source: `Deploy from a branch`, Branch: `main` / `(root)` → Save.
4. 1~2분 뒤 접속: `https://<GitHub사용자명>.github.io/<저장소명>/`

## 데이터 수정
데이터는 `index.html` 안의 `const DATA = [...]`에 들어 있습니다. `data.json`은 원본 보관용이며, 수정 시 `index.html`의 `DATA`도 함께 바꿔 주세요.
