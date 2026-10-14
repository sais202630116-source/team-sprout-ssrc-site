# Team SPROUT | SSRC 소개 웹사이트

서울시교육청이 주관한 제1회 서울 학생 로봇 대회(Seoul Student Robot Competition, SSRC)에 참가한 고교생 팀 **Team SPROUT**를 소개하는 반응형 웹사이트입니다. 로봇 제작, 기획, 마케팅, 회계, 운영의 융합 역량과 팀의 대회 활동을 안내합니다.

## 화면 구성

- **홈**: Team SPROUT 로고, SSRC 참가 소개, 다섯 역할 요약, 대회 활동 미리보기
- **팀 소개**: 로봇 제작·기획·마케팅·회계·운영 역할 검색, 필터, CRUD
- **SSRC 도전**: 대회 활동 검색, 상태 필터, CRUD
- **문의하기**: 문의 등록·조회·삭제 및 JSON 백업

## 실행 방법

### VS Code + Live Server

1. 이 폴더를 VS Code에서 엽니다.
2. Live Server 확장 프로그램을 설치합니다.
3. `index.html`을 열고 **Go Live**를 선택합니다.

### 브라우저에서 직접 열기

`index.html`을 Chrome 또는 Edge에서 열 수 있습니다. 데이터베이스 기능은 브라우저의 IndexedDB를 사용합니다. 로컬 파일 실행에서 브라우저 저장소가 제한되면 Live Server로 실행하세요.

## 데이터 저장

팀 역할, 활동, 문의 정보는 현재 브라우저의 IndexedDB에 저장됩니다. 서버 전송이나 기기 간 동기화는 구현하지 않았습니다. 문의 화면의 **백업 내보내기**로 현재 데이터를 JSON 파일로 저장할 수 있습니다.

## 파일 구성

- `index.html` — 전체 화면과 상호작용을 포함한 정적 웹 앱
- `team-sprout-logo.png` — 제공된 로고 이미지에서 정리한 가로형 웹용 로고
- `team-sprout-icon.png` — 제공된 로고 이미지에서 정리한 심볼
- `UPLOAD_REPORT.md` — GitHub 업로드 과정에서 확인한 기술적 어려움과 조치

## 기술

HTML, CSS, JavaScript, IndexedDB. 별도의 빌드나 패키지 설치가 필요하지 않습니다.
