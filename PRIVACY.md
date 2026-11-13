# 다온HC (다온HC 고객) 개인정보처리방침

- **앱 이름**: 다온HC (다온HC 고객 / DaonHC Customer Desktop)
- **게시자**: 다온HC (DaonHC)
- **시행일**: 2026-11-13

## 1. 처리하는 개인정보 항목 및 목적
다온HC 프로그램은 제휴 약국 고객의 의약품 주문 및 제휴 도매사이트 업무 연동을 위해서만 최소한의 정보를 처리합니다.

1. **계약 약국 본인 확인 정보 (Google OAuth)**
   - 수집·조회 항목: Google 계정 기본 프로필(이메일 주소, 표시 이름)
   - 목적: 다온HC 승인 약국 사용자 인증 및 주문 화면 접근 제어
2. **제휴 도매사이트 연동 계정 정보**
   - 처리 항목: 사용자가 프로그램 내에 직접 입력한 제휴 의약품 도매사이트 아이디·비밀번호 및 로그인 세션
   - 저장 방식: **사용자 PC 로컬 폴더(`%APPDATA%\다온HC 고객`) 내에만 Windows DPAPI(safeStorage)로 암호화하여 저장**되며, 외부 서버로 판매하거나 제3자에게 공유하지 않습니다.
3. **주문 및 설정 데이터**
   - 처리 항목: 약국의 품목 조회·장바구니·주문 요청 내역 및 사용자 설정 백업 데이터
   - 전송 방식: HTTPS 암호화 통신을 통해 다온HC 주문 API 및 사용자가 선택한 도매사이트에만 전달됩니다.

## 2. 제3자 제공 및 광고·추적 여부
- 다온HC 프로그램은 사용자의 개인정보를 외부 제3자에게 판매, 임대 또는 광고 목적으로 공유하지 않습니다.
- 사용자 행태 추적(광고 SDK, 타사 트래커 등)을 포함하지 않습니다.

## 3. 보유 기간 및 파기 방법
- 사용자는 프로그램 내 로그아웃, 도매사이트 계정 삭제, 또는 프로그램 제거 및 로컬 AppData(`%APPDATA%\다온HC 고객`) 폴더 삭제를 통해 저장된 로그인 정보 및 설정을 즉시 파기할 수 있습니다.

## 4. 문의처
- 다온HC 고객센터 / 프로그램 내 채팅·공지 문의 또는 지원 페이지: https://github.com/praktos100-create/daonHC-downloads/issues

---

# Privacy Policy Summary (English)

- **Application**: 다온HC (다온HC 고객 / DaonHC Customer Desktop)
- **Publisher**: 다온HC (DaonHC)
- **Effective Date**: 2026-11-13

DaonHC Customer Desktop is a B2B pharmacy ordering client used strictly by contracted pharmacies.
1. **Authentication**: Uses Google OAuth basic profile (email address and display name) solely to verify authorized pharmacy users.
2. **Local Credential Storage**: Partnered wholesale portal credentials entered by the user are encrypted locally on the user's PC inside `%APPDATA%\다온HC 고객` using Windows DPAPI (`safeStorage`) and are never sold or shared with unrelated third parties.
3. **Order Data & Security**: Order requests and cart actions are transmitted over HTTPS exclusively to DaonHC and user-selected wholesale portals.
4. **No Ads / No Third-Party Tracking**: The application contains no advertising SDKs or third-party behavioral tracking.
5. **Data Deletion & Contact**: Users can remove stored local credentials at any time by deleting portals, signing out, or removing `%APPDATA%\다온HC 고객`. Support: https://github.com/praktos100-create/daonHC-downloads/issues