# Beauty Report — Hair Report Releases

hair-report 데스크톱 앱의 **릴리즈 / 자동 업데이트 배포 전용** 레포입니다.

- **소스 코드는 여기 없습니다** → [`AnigmaDev/beauty-report-react`](https://github.com/AnigmaDev/beauty-report-react) (private monorepo, `apps/hair-report`).
- 이 레포의 릴리즈는 소스 레포의 GitHub Actions(`release-hair.yml`)가 `hair-v*` 태그 push 시 electron-builder로 빌드해 **자동 publish**합니다. 여기에 코드를 커밋하거나 릴리즈를 수동 생성하지 마세요.
- 설치된 앱의 electron-updater가 이 **public** 레포를 익명(토큰 없이)으로 조회해 자동 업데이트합니다.
- 릴리즈 태그는 `v{version}` (예: `v0.3.0`). 앱별 semver 독립.

배포 방법 전체는 소스 레포 README의 **"Release & 자동 업데이트"** 섹션을 참고하세요.
