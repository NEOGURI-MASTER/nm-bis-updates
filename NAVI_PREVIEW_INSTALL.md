# NM-BIS NAVI PREVIEW — 휴대폰·태블릿 설치

## ✅ 고정 서명 시험판 다운로드

**[NM-BIS NAVI PREVIEW APK 다운로드](https://raw.githubusercontent.com/NEOGURI-MASTER/nm-bis-updates/navi-preview/NM_BIS_NAVI_PREVIEW_LOGIN_835ec2b95a0f.apk)**

- 용도: 로그인 · 기기등록 · GM-1009 정류장 개략도 시안 시험
- 설치 방식: 정식 NM-BIS와 **별도 앱** (패키지 `kr.co.nugurimotors.nmbis.navpreview`)
- 파일 크기: 17.2 MiB
- 파일 SHA-256: `835ec2b95a0f1f96169f80ddbbd4476553c8ae688259c00e1167e2944f297824`
- 빌드 및 공개 파일 검증: [GitHub Actions 성공](https://github.com/NEOGURI-MASTER/nm-bis/actions/runs/40346460422)
- 새 빌드부터 **고정 서명 인증서 + 증가하는 versionCode** 적용

## 이미 예전 NAVI PREVIEW를 설치한 경우

**예전 파일은 GitHub 실행마다 달라지는 임시 디버그 서명**으로 만들어져 현재 새 APK와 서명이 다를 수 있습니다. **한 번만** 다음 순서를 따라 주세요.

1. 기존 정식 **NM-BIS는 절대 삭제하지 않습니다.**
2. NM-BMS 관리자페이지 → **NM-BIS 사용자 / 기기 → 등록 기기**에서 이전 시험판 기기를 등록 해제합니다. (앱 재설치 후 다시 등록됩니다.)
3. 휴대폰 **설정 → 애플리케이션 → NM-BIS NAVI PREVIEW → 삭제**
4. 위의 고정 서명 APK를 내려받아 다시 설치합니다.
5. NM-BMS에 등록한 **성명 + 생년월일 8자리(YYYYMMDD)**로 로그인합니다.
6. NM-BMS 등록 기기에서 새 기기가 **1/3대** 등으로 표시되는지 확인합니다.

**이후에는 동일 서명을 유지하는 새 APK로 업데이트할 수 있도록 빌드 파이프라인을 수정했습니다.**

## 주의 사항

- Google Play 프로텍트가 경고하는 경우 무리하게 보안을 끄거나 반복 우회하지 말고 관리자에게 알려주세요. APK의 빌드 검증과 Google의 앱 안전성 검사는 서로 다릅니다.
- Galaxy의 **보안 위험 자동 차단**이 켜져 있으면 스토어 외부 앱 설치가 추가 차단될 수 있습니다. 보안 설정을 변경하기 전에 원인을 확인하세요.
- NAVI 화면의 정류장 연결선은 **실제 도로 경로가 아닌 개략도**입니다. TMAP Navi SDK 음성 길안내는 아직 지원하지 않습니다.
- 현재는 로그인과 화면 구성 검증용입니다. **승객TV·안내방송이 필요한 실제 운행에 사용하지 마세요.**
- 공개 APK에는 권한을 제한한 앱 전용 로그인 키가 포함되므로, **성명/생년월일 및 등록기기 승인 관리**는 반드시 유지해야 합니다.

이 페이지 주소는 기존 QR코드에 연결된 **고정 설치 안내 주소**입니다.
