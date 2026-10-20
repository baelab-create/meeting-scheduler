# meeting-scheduler

박성훈·배원규·신재만 교수 미팅 일정 조율 페이지 (GitHub Pages).

- `index.html` 단일 파일
- 저장: Firebase `baelab-ledger` 프로젝트 Firestore `meeting/{링크 키}` 문서 하나 (규칙은 baelab-ledger 저장소 `firestore.rules`)
- 접속: `index.html?k=<링크 키>` — 키 없는 링크는 읽기·쓰기 불가
- 이번 주 + 다음 주 2주만 표시, 결과 탭의 전체 리셋으로 새 일정 시작
