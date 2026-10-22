# LinkCatch

광고 없는 Windows 10/11 64비트 미디어 도구의 배포 파일과 앱 업데이트 안내입니다.

## 처음 설치

1. [최초 설치 ZIP 다운로드](https://github.com/promise0627/linkcatch-updates/releases/download/v1.2.0/LinkCatch-1.2.0-setup.zip)
2. ZIP 전체를 압축 해제하고 `LinkCatch` 폴더의 `Install.cmd`를 실행합니다.
3. 공식 배포처에서 변환 도구를 다운로드하고 검증한 뒤 앱이 실행됩니다. 인터넷 연결이 필요합니다.
4. 다음부터는 `LinkCatch.exe`를 실행합니다. Python 별도 설치는 필요하지 않습니다.

## 기존 1.0 / 1.1 사용자

[최초 연결 패치](https://github.com/promise0627/linkcatch-updates/releases/download/v1.2.0/LinkCatch-1.2.0-bootstrap.zip)를 압축 해제하고 앱을 종료한 뒤 `apply-update.cmd`를 실행하여 기존 앱 폴더를 지정합니다.
이후에는 앱의 **앱 업데이트** 버튼으로 새 버전을 받을 수 있습니다. 기존 앱이 없다면 최초 설치 ZIP을 사용하세요.

## 업데이트

- 앱 업데이트: 새 앱 버전의 변경 파일 다운로드 → SHA256 검증 → 교체 → 재시작
- 엔진 갱신: 공식 배포처의 yt-dlp 업데이트
- [배포 버전과 검증용 체크섬](https://github.com/promise0627/linkcatch-updates/releases/latest)

최초 설치본에는 앱 런타임과 Node.js가 포함됩니다. yt-dlp와 FFmpeg/ffprobe 실행 파일은 ZIP에 포함하지 않으며, 설치 시 공식 GitHub 배포처에서 고정 버전을 직접 다운로드하고 SHA256을 검증합니다.
라이선스 및 출처는 ZIP의 `licenses`와 `THIRD_PARTY_NOTICES.txt`를 확인하세요.

본인이 다운로드·변환할 권한이 있는 미디어에 사용하세요. 로그인·DRM·라이브는 지원하지 않습니다.

이 저장소에는 공개 배포 파일과 안내만 보관합니다.
