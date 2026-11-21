# AiKjvplus public research data

일반 사용자가 GitHub 로그인 없이 받을 수 있는 공개 배포 저장소입니다.

- `research_manifest.json`: 앱이 사용하는 공개 자료 목록과 SHA-256
- `dictionary_version.json`: 사전 버전·표제어 수 메타데이터만 포함
- 성경 본문, 원본 PDF, 그림, 도표, 비공개 검토자료는 이 저장소에 배포하지 않습니다.
- `niv_apostasy.json`은 기존 파일이며 앱 자동 적용 대상이 아닙니다. 배포 권한과 앱 구조 지원을 별도로 검토해야 합니다.

검증 및 배포 권한이 모두 확인된 자료만 manifest에서 `supported`, `auto_download: true`로 등록합니다.