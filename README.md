# LinkCatch

Windows 10/11 64비트 미디어 다운로드·변환 앱입니다.

## 파일 하나로 실행

[LinkCatch.exe 다운로드](https://github.com/promise0627/linkcatch-updates/releases/latest/download/LinkCatch.exe)

받은 EXE 하나를 원하는 폴더에 두고 실행하세요. 별도 설치 프로그램과 Python 설치가 필요 없습니다. [ZIP으로 받기](https://github.com/promise0627/linkcatch-updates/releases/latest/download/LinkCatch-win64.zip)도 가능합니다.

첫 실행에 필요한 다운로드·변환 도구는 공식 배포처에서 내려받고 SHA256을 확인합니다. 도구와 설정은 `%LOCALAPPDATA%\LinkCatch`에서 관리합니다.

빠른 다운로드는 16개 조각을 병렬로 받고 10MB HTTP 연결 분할을 사용합니다. 조각 파일과 분리된 영상·음성은 앱 임시 폴더에서 처리하므로 선택한 저장 폴더에는 완성 파일만 표시됩니다. 실제 속도는 영상 CDN과 인터넷 회선에 따라 달라집니다.

## 기존 사용자 업데이트

- **1.2.0 이상** 사용자는 **앱 업데이트** 버튼으로 받습니다.
- **1.0 / 1.1** 사용자는 새 EXE를 사용하거나 [최초 연결 패치](https://github.com/promise0627/linkcatch-updates/releases/download/v1.3.1/LinkCatch-1.3.1-bootstrap.zip)를 한 번 적용합니다.
- **엔진 갱신** 버튼은 공식 배포처의 yt-dlp를 갱신합니다.

[릴리스 및 SHA256 체크섬](https://github.com/promise0627/linkcatch-updates/releases/latest)

본인이 다운로드·변환할 권한이 있는 미디어에 사용하세요. 로그인·DRM·라이브는 지원하지 않습니다.
