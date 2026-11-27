# Tasks Widget 개인정보처리방침

시행일: 2026년 11월 27일

Tasks Widget(이하 "위젯")은 Windows 바탕화면에서 사용자의 Google Tasks를 표시하고 관리하기 위한 데스크톱 프로그램입니다. 본 방침은 위젯이 사용자의 Google 계정 데이터와, 사용자가 직접 보내는 피드백을 어떻게 다루는지 설명합니다.

## 1. 접근하는 데이터

위젯은 Google OAuth를 통해 사용자가 동의한 경우에만 아래 권한을 요청합니다.

- **Google Tasks** (`https://www.googleapis.com/auth/tasks`): 사용자의 할 일 목록과 할 일을 조회, 추가, 수정, 완료 처리하기 위해 사용합니다.

위젯은 그 밖의 Google 데이터(Gmail, 드라이브, 캘린더, 연락처 등)에 접근하지 않습니다.

## 2. 데이터 사용 목적

Google Tasks 데이터는 오직 위젯 화면에 할 일을 표시하고, 사용자가 위젯에서 요청한 변경(추가, 수정, 완료 등)을 Google Tasks에 반영하는 데에만 사용됩니다. 광고, 프로파일링, 분석 등 다른 목적으로 사용하지 않습니다.

## 3. 데이터 저장 및 보호

- 위젯에는 별도의 서버가 없습니다. 할 일과 관련된 모든 통신은 사용자 PC에서 Google API로 직접 이루어집니다.
- 로그인 토큰과 할 일 캐시는 **사용자 PC에만** 저장되며, Windows DPAPI로 암호화되어 해당 Windows 사용자 계정에서만 읽을 수 있습니다.
- 개발자는 사용자의 Google 계정 정보, 토큰, 할 일 데이터를 수집하거나 보관하지 않습니다.

## 4. 피드백 보내기 (선택)

위젯 메뉴의 `피드백 보내기`는 사용자가 직접 글을 쓰고 `보내기`를 누를 때에만 동작합니다. 사용하지 않으면 아무것도 전송되지 않습니다.

- **보내는 항목:** 사용자가 적은 글, 위젯 버전. 할 일, Google 계정 정보, 로그인 토큰, PC 정보는 보내지 않습니다.
- **목적:** 오류 확인과 기능 개선에만 사용합니다.
- **전달 방식:** 개발자의 Google Forms(Google LLC 운영, 서버가 미국 등 국외에 있을 수 있음)로 전송·보관됩니다. 전송 과정에서 Google은 서비스 운영을 위해 접속 정보(IP 주소 등)를 처리할 수 있으며, 개발자에게는 적은 글과 버전, 받은 시각만 보입니다.
- **보관 기간:** 받은 날로부터 1년이 지나거나 처리가 끝나면 삭제합니다.
- **주의:** 이름, 연락처 등 개인정보는 적지 않아도 됩니다. 답변이 필요해 연락처를 적은 경우 답변 목적으로만 사용하고 위 기간 안에 삭제합니다.
- **보내는 양 제한:** 실수나 악용을 막기 위해 한 PC에서 하루 5번, 1분에 한 번까지 보낼 수 있습니다. 이를 위해 보낸 시각만 사용자 PC에 기록합니다.
- 삭제를 원하면 아래 문의처로 보낸 날짜와 대략의 내용을 알려 주세요.

## 5. 제3자 제공

위젯은 사용자의 Google 데이터를 개발자 또는 어떠한 제3자에게도 전송, 판매, 공유하지 않습니다. 할 일 데이터는 사용자 PC와 Google 사이에서만 오갑니다. 4항의 피드백은 사용자가 직접 보낸 내용만 위 방식으로 개발자에게 전달됩니다.

## 6. Google API 서비스 사용자 데이터 정책 준수

위젯이 Google API로부터 받은 정보의 사용 및 다른 앱으로의 전송은 제한적 사용(Limited Use) 요건을 포함한 [Google API 서비스 사용자 데이터 정책](https://developers.google.com/terms/api-services-user-data-policy)을 준수합니다.

## 7. 접근 권한 철회 및 데이터 삭제

- 언제든지 [Google 계정 > 보안 > 서드파티 앱 및 서비스](https://myaccount.google.com/connections)에서 Tasks Widget의 접근 권한을 철회할 수 있습니다.
- 위젯을 삭제하거나 위젯에서 로그아웃하면 PC에 저장된 토큰과 캐시를 제거할 수 있습니다.

## 8. 방침 변경

본 방침이 변경되는 경우 이 페이지에 게시하며, 상단의 시행일을 갱신합니다.

## 9. 문의

개인정보 관련 문의: tjdwns4570@gmail.com

---

# Privacy Policy (English)

Effective date: November 27, 2026

Tasks Widget ("the widget") is a Windows desktop app that displays and manages your Google Tasks.

- **Data accessed:** Only the Google Tasks scope (`https://www.googleapis.com/auth/tasks`), used to read, create, update and complete your task lists and tasks. No other Google data is accessed.
- **Use:** Task data is used solely to show your tasks in the widget and apply changes you make. It is not used for advertising, profiling or analytics.
- **Storage:** There is no server. The widget talks directly to Google APIs from your PC. Sign-in tokens and a task cache are stored only on your PC, encrypted with Windows DPAPI.
- **Feedback (optional):** Only when you write a message in `Send feedback` and press Send, the widget sends that message and the widget version to the developer's Google Form (operated by Google LLC, possibly stored outside Korea). No tasks, account data, tokens or PC information are sent. Feedback is used only to fix bugs and improve the widget and is deleted within one year. Sending is limited to 5 times a day per PC.
- **Sharing:** Your Google data is never sent to the developer or any third party, and nothing is sold or shared. Only feedback you choose to send reaches the developer.
- **Google API policy:** The widget's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.
- **Revoking access:** You can revoke access at any time in your [Google Account connections](https://myaccount.google.com/connections). Uninstalling the widget or signing out removes the locally stored token and cache.
- **Contact:** tjdwns4570@gmail.com
