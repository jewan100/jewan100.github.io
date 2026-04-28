# zipkr 개인정보 처리방침

본 앱(이하 "zipkr")은 한국 우편번호·도로명주소 검색 서비스를 제공합니다. 본 방침은 zipkr가 수집·사용·이전하는 정보의 범위와 목적을 설명합니다.

## 1. 수집하는 정보

### 1.1 사용자가 입력하는 정보
- **검색어**: 사용자가 입력한 도로명·지번·건물명 텍스트는 외부 API(아래 §3)에 전송되어 검색 결과를 받기 위해 사용됩니다. zipkr는 검색어를 자체 서버에 저장하지 않으며, 기기 외부에 영구 보관하지도 않습니다.

### 1.2 자동으로 수집되는 정보
- **광고 식별자(GAID)**: Google AdMob을 통해 맞춤형 광고를 제공하기 위해 수집됩니다.
- **크래시 로그·기기 정보**: 앱이 비정상 종료된 경우 Firebase Crashlytics가 스택 트레이스, 기기 모델·OS 버전 등을 자동으로 수집합니다. 안정성 개선 외 목적으로는 사용되지 않습니다.
- **사용성 분석 정보**: Firebase Analytics가 화면 방문·이벤트 발생 횟수 등 익명 집계 정보를 수집합니다.

### 1.3 수집하지 않는 정보
- 위치 권한, 연락처, 사진/저장소, 카메라, 마이크, 통화 기록 등 민감 권한은 일절 요청·수집하지 않습니다.
- 사용자 계정·로그인 기능이 없으므로 이메일·비밀번호·이름 등 식별 가능 개인정보를 수집하지 않습니다.

## 2. 사용 목적

수집된 정보는 다음 목적으로만 사용됩니다.

- 우편번호·주소 검색 결과 제공 (사용자 입력 검색어)
- 지도 표시 및 외부 지도 앱 연계 (검색 결과의 좌표)
- 맞춤형 광고 제공 (광고 식별자)
- 앱 안정성 개선 및 버그 수정 (크래시 로그)
- 기능 개선을 위한 익명 사용 통계 (분석 정보)

## 3. 외부 서비스(SDK·API) 연동

zipkr는 다음 외부 서비스를 사용합니다. 각 서비스의 정보 처리 방침은 해당 회사가 별도로 공시합니다.

| 서비스 | 용도 | 정책 |
|---|---|---|
| Google AdMob | 광고 표시 | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Firebase Crashlytics | 크래시 자동 수집 | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Firebase Analytics | 익명 사용 통계 | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| 행정안전부 도로명주소 API | 주소 검색 | [business.juso.go.kr](https://business.juso.go.kr) |
| 카카오 로컬 API | 좌표 변환 (geocoding) | [kakao.com/policy/privacy](https://www.kakao.com/policy/privacy) |
| 카카오맵 JavaScript SDK | 지도 표시 (WebView 임베드) | [kakao.com/policy/privacy](https://www.kakao.com/policy/privacy) |

## 4. 정보의 국외 이전

Google·Firebase 관련 정보는 미국에 위치한 Google 데이터 센터로 이전될 수 있습니다. 카카오·행안부 데이터는 대한민국 내 서버에서 처리됩니다.

## 5. 보관 기간

- **검색어**: 자체 보관 없음 (외부 API 응답을 받은 즉시 사용 후 폐기)
- **크래시 로그**: Firebase Crashlytics 기본 보관 기간(약 90일)
- **광고 식별자**: 사용자가 기기 설정에서 언제든 재설정 또는 삭제 가능

## 6. 사용자 권리

- **광고 식별자 재설정·삭제**: 안드로이드 기기 **설정 → Google → 광고 → 광고 ID 삭제**
- **맞춤형 광고 거부**: 위 설정에서 "맞춤 광고 선택 해제"
- 거부 후에도 zipkr의 핵심 기능(주소·우편번호 검색)은 정상 이용 가능합니다.

## 7. 14세 미만 아동 정보

zipkr는 14세 미만 아동을 대상으로 하지 않으며, 의도적으로 아동 개인정보를 수집하지 않습니다.

## 8. 정책 변경

본 방침은 법령·서비스 변경 등에 따라 수정될 수 있으며, 변경 시 본 페이지를 통해 공지합니다.

## 9. 문의

개인정보 처리에 관한 문의는 **hawaii1468@gmail.com** 으로 연락해 주세요.

---

**앱 이름**: zipkr (우편번호)
**패키지**: com.jewan.zipkr
**최종 업데이트**: 2026년 4월 28일
