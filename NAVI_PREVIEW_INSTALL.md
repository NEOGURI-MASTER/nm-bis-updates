# NM-BIS NAVI PREVIEW — 카카오 지도 빈 화면 수정판

**최신 시험 APK: 6.7.46-NAVI-PREVIEW / 빌드 #1000047**

## 다운로드

**[NAVI PREVIEW 최신 APK 다운로드](https://raw.githubusercontent.com/NEOGURI-MASTER/nm-bis-updates/navi-preview/NM_BIS_NAVI_PREVIEW_LOGIN_540246f3ce43.apk)**

- 기반: 검증된 NM-BIS 6.7.46 / build 164
- 독립 패키지: `kr.co.nugurimotors.nmbis.navpreview`
- SHA-256: `540246f3ce43a58c731fb02ddcd624bc2260413223649380f95a8325f8a0fe21`
- [Android 빌드·테스트·고정서명·공개 다운로드 검증 성공](https://github.com/NEOGURI-MASTER/nm-bis/actions/runs/40475555815)

## 이번 수정 사항

- Samsung 태블릿/DeX에서 지도 영역이 초기화되기 전에 지도가 생성되는 경우 예방
- 화면 크기 변경 시 카카오 지도 재배치 (`relayout`)
- 지도가 실제로 그려졌는지 확인할 때까지 로딩 상태 유지
- SDK HTTP 401/403/429 또는 지도 타일 미표시 시 원인을 구분할 수 있는 오류 문구 표시
- 기존 GPS, 16개 정류장, 일반/다크 화면과 독립 실행 패키지 유지

## 이미 NAVI PREVIEW가 설치되어 있다면

1. **기존 NAVI PREVIEW를 삭제하지 마세요. 기기 등록을 해제하지도 마세요.**
2. 위의 최신 APK를 다운로드하고 기존 NAVI PREVIEW 앱 위에 업데이트 설치합니다.
3. 실행 후 좌측 하단 빌드번호가 **#1000047**인지 확인합니다.
4. '내비 시안' → '실제 지도'로 16개 정류장/지도 타일 확인, '개략도' 전환도 확인합니다.
5. 위치 권한을 묻는다면 NAVI PREVIEW 앱에 필요한 위치 접근을 허용합니다.

정상적으로 고정 서명 APK를 설치한 경우 기존 로그인 및 등록 기기 정보가 유지되어야 합니다.
**서명 충돌이 발생할 때에만** 이전 디버그 서명 앱인지 먼저 확인하세요. 계정·기기 정보를 확인하지 않고 삭제·보안 우회를 하지 마세요.

## 지도가 여전히 비어 있을 때

- `KAKAO_HTTP_401`, `KAKAO_HTTP_403`: 카카오 개발자 콘솔에서 해당 JavaScript 키의 **JavaScript SDK 도메인**에 `https://appassets.androidplatform.net` 등록 여부 및 **카카오맵 API 사용 설정 ON** 확인
- `KAKAO_HTTP_429`: 지도 쿼터/사용량 확인
- `MAP_TILE_TIMEOUT`: 인터넷 연결 및 WebView·카카오 지도 타일 응답 확인
- `MAP_SIZE_ZERO`, `MAP_RELAYOUT`: 태블릿/DeX 레이아웃 오류 코드. 화면을 캡처하여 개발팀에 전달

**실제 도로 주행 경로 안내가 아닙니다.** 지도 위 정류장 연결선은 직선 개략도이며, TMAP 음성 길안내/버스 통행 가능 경로 검증은 아직 없습니다. 승객 TV 및 안내방송과의 실차 운행 동시 사용은 검증 전까지 하지 마세요.

정식 NM-BIS 설치 파일/자동 업데이트/차량 운행 앱은 변경되지 않습니다. 이 설치 페이지는 기존 NAVI QR 코드와 연결된 고정 주소입니다.
