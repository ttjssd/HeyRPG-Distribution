# HeyRPG Distribution

HeyRPG 친구용 클라이언트 배포 전용 저장소입니다. 개발 소스·서버·계정 정보는 포함하지 않습니다.

## 친구 설치
[최신 HeyRPGLauncher.exe 다운로드](https://raw.githubusercontent.com/ttjssd/HeyRPG-Distribution/main/HeyRPGLauncher.exe) 파일 하나만 받으세요. 실행 → 설치 폴더 선택 → Microsoft 로그인 → 게임 시작.
Minecraft Java 이용 권한이 필요합니다. 필요한 Java / Minecraft / Fabric / 필수 모드 / 리소스팩을 런처가 준비합니다.
기존 .minecraft는 수정하지 않습니다. Windows x64용입니다. 정품 계정 없는 오프라인 우회는 지원하지 않습니다.

## 파일 출처
Minecraft와 Java는 공식 메타데이터에서, Fabric은 공식 Fabric 메타데이터에서 받습니다.
외부 모드는 공식 Modrinth 배포 URL을 사용합니다. 자체 ClientUI와 리소스팩은 이 저장소의 Releases에서 받습니다.
manifest.json에 SHA256, 크기, 버전, 서버 설정을 기록합니다. versions.json에 실제 파일 정보를 기록합니다.

## 로그인 연결
Microsoft 로그인 Client ID가 배포 설정에 반영되어 있습니다. 친구가 Client ID를 입력할 필요는 없습니다.
실제 로그인 및 Minecraft API 권한은 운영자가 직접 로그인하여 확인해야 합니다.

이 배포는 Mojang 또는 Microsoft의 공식 제품이 아닙니다.

## 자동 업데이트
런처 1.1.0부터 자체 업데이트와 관리 모드·팩 교체를 지원합니다. 구버전 관리 파일은 누적 보관하지 않습니다. 개인 모드·개인 팩은 보존합니다.
기존 1.0.2에는 자동 교체 기능이 없어 1.1.0을 한 번 받아야 합니다. 이후 같은 EXE를 사용하세요.
