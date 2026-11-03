# SHIPLAB — 웹앱 배포 실습 시뮬레이터

ChatGPT에서 코드를 만들고 GitHub에 저장한 뒤 Vercel로 배포하는 과정을 연습하는 **비공식 교육용 웹앱**입니다.

## 실습 진행 순서

1. ChatGPT와 유사한 화면에서 홈페이지 프롬프트 입력, 모의 HTML 생성, 코드 복사
2. GitHub 홈페이지로 이동 → Sign in → 가상 로그인
3. New repository → 저장소 생성 → Add file 메뉴 → Create new file
4. index.html에 코드 붙여넣기 → Commit changes 팝업에서 커밋
5. Vercel 홈페이지로 이동 → Log in → Continue with GitHub
6. GitHub OAuth의 Authorize Vercel 팝업 → Install Vercel 팝업 → 저장소 접근 범위 선택
7. Vercel 대시보드 → Add New → Project → GitHub 저장소 Import
8. Framework Preset Other → Deploy → 모의 배포 로그 → 결과 페이지 Visit

## 안전 안내

- GitHub/Vercel 로그인과 권한 승인은 시뮬레이터 내부에서만 재현합니다.
- 실제 계정 인증·권한 승인 및 GitHub·Vercel API 연동은 실행하지 않습니다.
- 학생은 실제 비밀번호를 입력하지 않습니다. 비밀번호 표시창은 읽기 전용입니다.
- 모의 URL 형식의 주소는 인터넷에 발급되지 않습니다.
- 이 시뮬레이터 웹앱 자체는 실제 GitHub → Vercel에 공개 배포할 수 있습니다.

## Vercel 배포 방법

GitHub 저장소 Choiceosori/Vibecoding을 Vercel New Project에서 가져옵니다. Framework Preset은 Other, Root Directory는 `./`, Build Command는 사용하지 않습니다. root index.html이 시작 파일입니다.
