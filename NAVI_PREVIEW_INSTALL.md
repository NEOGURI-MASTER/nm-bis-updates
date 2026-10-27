# NM-BIS NAVI PREVIEW — 카카오 지도 및 GPS 시험판

## 신규 APK 다운로드

**[NAVI PREVIEW 실제 지도/GPS 시험판 다운로드](https://raw.githubusercontent.com/NEOGURI-MASTER/nm-bis-updates/navi-preview/NM_BIS_NAVI_PREVIEW_LOGIN_ea09296d1340.apk)**

- 기반: NM-BIS 6.7.46-TEST
- 별도 패키지: `kr.co.nugurimotors.nmbis.navpreview`
- 파일 크기 약 17.3 MiB
- SHA-256: `ea09296d134089bffea1bab89230c33b98c0288f98d0296dbb06ccfd958a3e9a`
- [빌드 및 고정서명 검증 성공](https://github.com/NEOGURI-MASTER/nm-bis/actions/runs/40364090907)

## 이번 변경

- 카카오 실제 지도 배경에 정류장 마커 전체 표시
- 현재 GPS 위치를 출발지 마커로 표시하고, 위치 권한 요청 버튼 제공
- `노선 전체` · `내 위치` 및 `실제 지도/개략도` 전환
- NM-BIS 실제 선택 노선/정류장 좌표 우선, 좌표 누락 시 경고
- 휴대폰/태블릿 지원, 일반/다크 테마 유지

## 설치 및 시험 순서

1. 이미 고정 서명 NAVI PREVIEW를 설치했다면 **삭제하지 말고 업데이트 설치**합니다. 
2. 실행 후 `내비 시안` 메뉴를 열고 `위치 권한 요청`이 보이면 위치를 허용합니다.
3. 지도 위 GM-1009 정류장 16개, 현재위치, `노선 전체`, `내 위치`를 확인합니다.
4. 카카오 지도가 로드되지 않으면 Kakao Developers에서 **JavaScript SDK 도메인 `https://appassets.androidplatform.net` 등록**을 다시 확인합니다.

**주의:** 지도는 실제 카카오 지도이지만 파란·녹색 연결선은 **도로 경로가 아닌 정류장 간 직선**입니다. 음성 길안내·턴바이턴·실도로 주행 안내 기능은 아직 없습니다. 실제 차량 운행에는 사용하지 마세요.

기존 운영 NM-BIS는 삭제하거나 변경하지 마세요. NAVI PREVIEW와 운영 NM-BIS를 같은 TV/차량 오디오에 동시에 연결하지 마세요.

이 페이지는 기존 QR코드가 가리키는 고정 설치 안내 주소입니다.
