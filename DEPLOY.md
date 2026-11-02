# PTE오팔 GitHub Pages 배포

1. 이 저장소의 Code 탭에서 **Add file → Upload files**를 선택합니다.
2. `pte_opal_github_ready/index.html` 파일을 저장소 최상위(root)에 업로드합니다. **GitHub에 업로드할 것은 공개용 정적 파일뿐입니다.**
3. Settings → Pages → Build and deployment에서 **Deploy from a branch**, **main**, **/(root)**를 선택한 뒤 Save합니다.
4. 공개 주소: https://dandelionmedia.github.io/PTE58/
5. Firebase Console → Authentication → Settings → Authorized domains에 `dandelionmedia.github.io`를 추가합니다.
6. Firebase 웹앱 설정과 Functions, Firestore 규칙을 별도로 설치·배포해야 Google 로그인, 데이터 저장, AI 문제 생성이 동작합니다.

**보안**: OpenAI API 키, Firebase 서비스 계정 JSON 및 서버 비밀키를 GitHub 공개 저장소에 올리지 마세요.

**참고**: Firebase Authentication 웹 설정값은 공개 가능하지만, Firebase 서버측 API 비밀키는 공개할 수 없습니다.
