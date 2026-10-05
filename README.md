# jC-STUDIO Updates

jC-STUDIO의 온라인 업데이트 저장소입니다.

## 업데이트 채널

- `latest.json` — STABLE 채널. 검증 완료 버전만 배포합니다.
- `latest-dev.json` — DEV 채널. 개발/테스트 버전을 배포합니다.

## 기본 원칙

업데이트는 jC-STUDIO의 App 코드만 교체합니다. `Engine`, `Models`, `Songs`, `Settings`는 유지합니다.

업데이트 적용 전 기존 App 파일을 자동 백업하고, 업데이트 ZIP의 SHA-256 값이 등록된 경우 무결성을 확인한 뒤 Python compile 검사를 통과한 파일만 적용합니다.

## 현재 기준 버전

- STABLE: V3.1.7.9
- DEV: V3.1.7.9

## 배포 파일

향후 업데이트 ZIP을 업로드한 뒤 각 manifest의 `url`과 `sha256`을 갱신합니다.
