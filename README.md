## doit-hc — 실습 파일 사용 안내

이 저장소에는 책에서 설명한 예제 HTML/CSS 파일들이 정리되어 있습니다. 이 문서는 독자들이 로컬에서 실습용 파일을 내려받아 열어보거나 개발 환경에서 편리하게 사용할 수 있도록 2가지 방법을 안내합니다.

---

## 방법 1 — GitHub에서 ZIP 파일로 다운로드 

1. 페이지 우측 상단의 녹색 버튼 "Code"를 클릭합니다.
2. 열리는 메뉴에서 "Download ZIP"을 클릭하면 ZIP 파일이 내려옵니다.
3. 내려받은 ZIP 파일의 압축을 풉니다.
4. 압축을 푼 폴더를 VS Code의 작업 폴더로 추가합니다.

---

## 방법 2 — 저장소를 클론해서 사용하는 방법

이 방법은 저장소의 전체 소스와 변경 이력을 내려받아 로컬에서 관리할 수 있습니다. Git이 설치되어 있어야 합니다.

1. 터미널(또는 PowerShell)을 엽니다.
2. 원하는 위치로 이동한 뒤 아래 명령을 실행합니다.

PowerShell (Windows) 예시:

```powershell
git clone https://github.com/funnycom/doit-hc.git
cd doit-hc
```

SSH를 사용하려면 (SSH 키 설정이 되어 있는 경우):

```powershell
git clone git@github.com:funnycom/doit-hc.git
cd doit-hc
```

장점:
- 저장소를 최신 상태로 유지하고 변경 사항을 직접 커밋할 수 있습니다.

---

문제 해결 및 추가 참고
- Git 설치가 안 되어 있으면: https://git-scm.com/downloads
- Windows에서 PowerShell 대신 Git Bash를 사용해도 됩니다.
- 로컬에서 바로 열어도 되는 예제와, 서버가 필요할 수 있는 예제를 구분하세요 (예: 일부 미디어/경로 처리).

파일/폴더 예시
- 각 챕터 폴더(예: `02/`, `03/`, `04/`)에 해당 장의 실습 파일들이 들어 있습니다. 책의 예제를 따라 해당 폴더의 HTML 파일을 열어 실습하세요.

문의나 README 개선 요청이 있으면 이 저장소의 이슈(issue)를 이용하거나, README를 직접 수정한 뒤 Pull Request를 보내주세요.

감사합니다 — 즐거운 실습 되세요!
