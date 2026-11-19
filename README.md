# quilleaf

마크다운 노트 앱 quilleaf의 설치 파일을 올리는 곳입니다. 소스 코드는 비공개입니다.

## 설치

- **Windows**: `winget install dohyun06.Quilleaf` (등록 전에는 [Releases](https://github.com/dohyun06/quilleaf-releases/releases/latest)에서 `quilleaf_<버전>_x64-setup.exe`)
- **macOS**: `brew install --cask dohyun06/tap/quilleaf` 또는 Releases의 `quilleaf_<버전>_universal.dmg`
- **Android**: Releases의 `quilleaf_<버전>_arm64.apk`

## 처음 열 때 막히면

앱이 Apple 공증과 Windows 코드 서명을 받지 않았기 때문에 처음 한 번 경고가 뜹니다.

- **macOS**: 앱을 한 번 열어 본 뒤 시스템 설정 → 개인정보 보호 및 보안 → "그래도 열기". 또는 터미널에서 `xattr -dr com.apple.quarantine /Applications/quilleaf.app`
- **Windows**: SmartScreen 창에서 "추가 정보" → "실행"
- **Android**: 설치할 때 "출처를 알 수 없는 앱" 설치를 허용
