# 경조로그 공개 안내 사이트

Flutter 앱 소스와 분리된 정적 소개 사이트입니다. GitHub Pages의 `main` 브랜치 `/ (root)`에서 배포합니다. 별도 웹 서버나 빌드 과정이 필요하지 않습니다.

## 공개 경로

- 홈페이지: https://whdgus928.github.io/gyeongjolog-site/
- 개인정보처리방침: https://whdgus928.github.io/gyeongjolog-site/privacy.html
- 서비스 이용약관: https://whdgus928.github.io/gyeongjolog-site/terms.html
- 계정 및 데이터 삭제 안내: https://whdgus928.github.io/gyeongjolog-site/privacy.html#delete-account
- Google OAuth 로고 업로드 파일: `assets/icon.png` (384×384 PNG)

## 운영자가 확인할 사항

- Google Cloud 승인된 도메인에 `whdgus928.github.io`를 추가하고 필요 시 Search Console에서 소유권을 확인합니다. HTML 태그 방식의 실제 인증 코드를 발급받으면 `index.html`의 head에 추가합니다. 임의 인증값을 넣지 않습니다.
- OAuth callback URL은 기존 Supabase 설정을 유지합니다. 이 사이트 주소를 인증 콜백으로 넣지 않습니다.
- 정책은 현재 앱 구현과 기존 정책을 토대로 작성했습니다. 운영자의 법적 의무 전체가 검증된 것은 아닙니다. Supabase 실제 저장 리전, 국외 이전 관련 고지 항목, 문의자료 보존 정책을 확인하고 필요한 내용을 보완해야 합니다.
- 개인정보처리방침의 삭제 절차는 운영자가 메일을 확인하여 직접 처리하는 방식입니다. 계정 삭제 시 인증 계정뿐 아니라 원본 스냅샷과 백업 모두 처리해야 합니다. 이 사이트는 삭제 요청을 자동 처리하지 않습니다.
- 앱 안의 계정 삭제 진입점 및 기존 스토어/앱 정책 URL이 이 안내와 일치하는지 별도로 확인해야 합니다.
- 출시가 확정되면 홈페이지의 'Google Play 출시 준비 중' 문구를 실제 스토어 링크로 변경합니다.
- 스크린샷에는 테스트 예시 데이터를 사용했습니다. 실제 사용자의 개인정보가 담긴 화면으로 교체하지 않습니다.

## 변경 범위

HTML 3개, 공용 CSS, 기존 로고와 앱 스크린샷만 공개합니다. 앱 코드, 키, 인증 토큰, 사용자 데이터는 포함하지 않습니다. 외부 폰트, 분석 스크립트, 광고 SDK를 사용하지 않습니다.
