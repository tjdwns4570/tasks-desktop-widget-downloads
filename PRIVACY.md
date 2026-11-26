# Tasks Widget 개인정보처리방침

시행일: 2026년 11월 26일

Tasks Widget(이하 "위젯")은 Windows 바탕화면에서 사용자의 Google Tasks를 표시하고 관리하기 위한 데스크톱 프로그램입니다. 본 방침은 위젯이 사용자의 Google 계정 데이터를 어떻게 다루는지 설명합니다.

## 1. 접근하는 데이터

위젯은 Google OAuth를 통해 사용자가 동의한 경우에만 아래 권한을 요청합니다.

- **Google Tasks** (`https://www.googleapis.com/auth/tasks`): 사용자의 할 일 목록과 할 일을 조회, 추가, 수정, 완료 처리하기 위해 사용합니다.

위젯은 그 밖의 Google 데이터(Gmail, 드라이브, 캘린더, 연락처 등)에 접근하지 않습니다.

## 2. 데이터 사용 목적

Google Tasks 데이터는 오직 위젯 화면에 할 일을 표시하고, 사용자가 위젯에서 요청한 변경(추가, 수정, 완료 등)을 Google Tasks에 반영하는 데에만 사용됩니다. 광고, 프로파일링, 분석 등 다른 목적으로 사용하지 않습니다.

## 3. 데이터 저장 및 보호

- 위젯에는 별도의 서버가 없습니다. 모든 통신은 사용자 PC에서 Google API로 직접 이루어집니다.
- 로그인 토큰과 할 일 캐시는 **사용자 PC에만** 저장되며, Windows DPAPI로 암호화되어 해당 Windows 사용자 계정에서만 읽을 수 있습니다.
- 개발자는 사용자의 Google 계정 정보, 토큰, 할 일 데이터를 수집하거나 보관하지 않습니다.

## 4. 제3자 제공

위젯은 사용자의 데이터를 개발자 또는 어떠한 제3자에게도 전송, 판매, 공유하지 않습니다. 데이터는 사용자 PC와 Google 사이에서만 오갑니다.

## 5. Google API 서비스 사용자 데이터 정책 준수

위젯이 Google API로부터 받은 정보의 사용 및 다른 앱으로의 전송은 제한적 사용(Limited Use) 요건을 포함한 [Google API 서비스 사용자 데이터 정책](https://developers.google.com/terms/api-services-user-data-policy)을 준수합니다.

## 6. 접근 권한 철회 및 데이터 삭제

- 언제든지 [Google 계정 > 보안 > 서드파티 앱 및 서비스](https://myaccount.google.com/connections)에서 Tasks Widget의 접근 권한을 철회할 수 있습니다.
- 위젯을 삭제하거나 위젯에서 로그아웃하면 PC에 저장된 토큰과 캐시를 제거할 수 있습니다.

## 7. 방침 변경

본 방침이 변경되는 경우 이 페이지에 게시하며, 상단의 시행일을 갱신합니다.

## 8. 문의

개인정보 관련 문의: tjdwns4570@gmail.com

---

# Privacy Policy (English)

Effective date: November 26, 2026

Tasks Widget ("the widget") is a Windows desktop app that displays and manages your Google Tasks.

- **Data accessed:** Only the Google Tasks scope (`https://www.googleapis.com/auth/tasks`), used to read, create, update and complete your task lists and tasks. No other Google data is accessed.
- **Use:** Task data is used solely to show your tasks in the widget and apply changes you make. It is not used for advertising, profiling or analytics.
- **Storage:** There is no server. The widget talks directly to Google APIs from your PC. Sign-in tokens and a task cache are stored only on your PC, encrypted with Windows DPAPI.
- **Sharing:** No data is sent to the developer or any third party, and nothing is sold or shared.
- **Google API policy:** The widget's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.
- **Revoking access:** You can revoke access at any time in your [Google Account connections](https://myaccount.google.com/connections). Uninstalling the widget or signing out removes the locally stored token and cache.
- **Contact:** tjdwns4570@gmail.com
