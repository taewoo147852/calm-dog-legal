# 안놀랄개 Legal Site — GitHub Pages 배포

이 폴더는 GitHub Pages 프로젝트 사이트 `calm-dog-legal`의 정적 루트입니다. 별도 도메인이나 DNS 설정은 사용하지 않습니다.

공개 기준 URL:

- `https://taewoo147852.github.io/calm-dog-legal/` — 지원/법적 안내 홈
- `https://taewoo147852.github.io/calm-dog-legal/privacy/` — 개인정보 처리방침
- `https://taewoo147852.github.io/calm-dog-legal/terms/` — 이용약관
- `https://taewoo147852.github.io/calm-dog-legal/support/` — 지원 및 문의

## 배포

1. GitHub 계정 `taewoo147852`에 Public repository `calm-dog-legal`을 만듭니다.
2. **이 `legal-site` 폴더 안의 파일과 폴더를 repository 최상단(root)에 업로드**합니다. `legal-site` 폴더 자체를 한 단계 더 넣지 않습니다.
3. Repository의 `Settings → Pages`에서 `Deploy from a branch`, `main`, `/(root)`를 선택합니다.
4. Custom domain은 입력하지 않습니다. 이 배포본에는 `CNAME` 파일도 없습니다.
5. 배포 후 위 4개 URL을 Safari에서 확인합니다.
6. App Store Connect의 Privacy Policy URL에는 `https://taewoo147852.github.io/calm-dog-legal/privacy/`를 사용합니다.
7. App Store Connect의 Support URL에는 `https://taewoo147852.github.io/calm-dog-legal/support/`를 사용할 수 있지만, Apple 제출 전 실제 연락 가능한 이메일/전화/주소 중 필요한 연락처를 지원 페이지에 추가해야 합니다.

앱의 공개 URL은 `CALM/App/AppConfiguration.swift`에 중앙화되어 있습니다. GitHub 사용자명 또는 repository 이름을 바꾸면 앱 URL과 이 사이트의 절대 URL을 함께 갱신하세요.
