# NM-BIS NAVI PREVIEW — 카카오 지도/태블릿 수정판

**최신 시험 APK: 6.7.46-NAVI-PREVIEW / 빌드 #1000099**

## 다운로드

**[NAVI PREVIEW 최신 APK 다운로드](https://raw.githubusercontent.com/NEOGURI-MASTER/nm-bis-updates/navi-preview/NM_BIS_NAVI_PREVIEW_LOGIN_e7aecfabec18.apk)**

- 독립 시험판 패키지: `kr.co.nugurimotors.nmbis.navpreview`
- 파일 크기: 17.4 MiB
- SHA-256: `e7aecfabec1886503075bf980461bb9ee14cb21f142dded19036db889a050537`
- [최신 자동 빌드 검증 내역](https://github.com/NEOGURI-MASTER/nm-bis/actions/workflows/navi-preview-build.yml)

## 기존 NAVI PREVIEW가 설치되어 있으면

1. **기존 NAVI PREVIEW 앱을 삭제하지 마세요. NM-BMS 기기 등록도 해제하지 마세요.**
2. 위의 APK를 내려받아 기존 NAVI PREVIEW 앱 위에 업데이트 설치합니다.
3. 앱 실행 후 좌측 하단 빌드번호가 **#1000099**인지 확인합니다.
4. 내비 시안 → 실제 지도에서 지도 타일·정류장 마커를 확인합니다. 개략도 전환도 시험합니다.
5. 고정 서명이 일치하는 APK라면 로그인/기기 등록 정보가 유지됩니다.

서명 충돌 시에만 **임시 디버그 서명 APK**가 설치되었는지 확인한 후 관리자의 지원을 받으세요.
기존 앱을 무작정 삭제하거나 등록기기를 해제하지 마세요.

## 지도 오류 진단

- `KAKAO_HTTP_401` / `KAKAO_HTTP_403`: JavaScript SDK 도메인 `https://appassets.androidplatform.net` 및 카카오맵 API 사용 설정 확인
- `KAKAO_HTTP_429`: 지도 사용량/쿼터 확인
- `MAP_TILE_TIMEOUT`: 인터넷 연결 및 지도 타일 수신 확인
- `MAP_SIZE_ZERO` / `MAP_RELAYOUT`: 태블릿·DeX 크기 계산 오류. 화면 캡처 전달

## 안전 관련 주의

- 지도 바탕은 실제 카카오 지도이나 정류장 연결선은 **직선 개략도**이며 실제 도로 경로가 아닙니다.
- TMAP 길안내/대형버스 통행 제한/음성 길안내는 검증 전이며 실차 운행에 사용하지 마세요.
- 기존 NM-BIS 정식 앱·안내방송·승객 TV·자동 업데이트는 변경하지 않습니다.
- 공개 파일이라도 사용자 로그인에는 관리자가 등록한 계정 및 기기 승인이 필요합니다.

이 페이지는 기존 QR 설치 주소를 유지합니다.
