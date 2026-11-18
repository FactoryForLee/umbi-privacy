---
title: UmBi 개인정보처리방침 / Privacy Policy
---

[한국어](#한국어) · [English](#english)

---

# 한국어

## UmBi 개인정보처리방침

UmBi(이하 "앱")는 외출할 때 비 예보와 챙길 소지품을 알려 주는 앱입니다. 앱은 회원가입이나 로그인이 없고, 개발자가 운영하는 서버도 없습니다. 이 방침은 앱이 어떤 정보를 어떻게 다루는지 설명합니다.

- 최초 시행일: 2026년 11월 3일
- 최근 개정·시행일: 2026년 11월 18일

### 1. 처리하는 정보와 목적

| 정보                                              | 목적                     | 저장 위치                                                                               |
| ------------------------------------------------- | ------------------------ | --------------------------------------------------------------------------------------- |
| 대략적인 위치 (위도·경도)                         | 현재 위치의 비 예보 확인 | 날씨 조회 때 OpenWeather로 전송. 위치를 못 받을 때 쓰려고 마지막 위치 1개를 기기에 저장 |
| 신체 활동 (걷기 / 멈춤)                           | 외출 감지                | 기기 안에서만 사용, 외부로 보내지 않음                                                  |
| 외출 루틴 시간, 소지품 목록, 날짜별 기록, 앱 설정 | 앱 기능 제공             | 기기 안에만 저장                                                                        |
| 사용자가 직접 작성한 피드백                       | 문의 확인, 앱 개선       | 개발자의 Discord 채널로 전송                                                            |

- 앱은 정확한 위치(GPS 수준)를 요청하지 않고, 대략적인 위치만 사용합니다.
- 센서를 켜 두면 앱을 닫아 둔 동안에도(상주 알림이 표시됩니다) 외출이 감지될 때 위치를 확인해 비 예보를 조회합니다. 앱을 열 때도 마지막 위치를 갱신합니다. 센서를 끄면 백그라운드 위치 확인은 멈춥니다.
- 앱은 이름, 전화번호, 이메일 같은 정보를 받지 않습니다.
- 피드백에는 작성한 글만 전송되고, 기기 정보나 계정 정보는 함께 보내지 않습니다. 다만 전송 과정에서 IP 주소는 Discord에 전달됩니다. 피드백에 개인정보를 적지 않도록 주의해 주세요.

### 2. 외부 서비스

앱은 아래 외부 서비스를 사용합니다. 각 서비스는 자체 개인정보처리방침에 따라 정보를 처리합니다.

| 서비스                                      | 제공 정보                              | 목적                             | 방침                                          |
| ------------------------------------------- | -------------------------------------- | -------------------------------- | --------------------------------------------- |
| OpenWeather (OpenWeather Ltd., 영국)        | 대략적인 위치(위도·경도), IP 주소      | 날씨 예보 조회                   | <https://openweather.co.uk/privacy-policy>    |
| Google AdMob (Google LLC, 미국)             | 광고 ID, IP 주소, 기기 정보 등         | 광고 표시 (비개인화 광고만 요청) | <https://policies.google.com/privacy>         |
| Firebase Cloud Firestore (Google LLC, 미국) | IP 주소 등 접속 정보                   | 공지사항 불러오기 (읽기만 함)    | <https://firebase.google.com/support/privacy> |
| Discord (Discord Inc., 미국)                | 사용자가 작성한 피드백 글, IP 주소     | 피드백 전달                      | <https://discord.com/privacy>                 |

### 3. 국외 이전

앱 기능을 제공하는 데 필요한 범위에서 아래와 같이 정보가 국외로 이전됩니다. 이전 근거는 앱 기능 제공(이용 계약의 이행)에 필요한 처리로서 이 방침에 공개하는 것입니다 (개인정보 보호법 제28조의8 제1항 제3호).

| 이전받는 자 (연락처) | 국가 | 이전 항목 | 이전 시기·방법 | 목적 | 보유 기간 |
| --- | --- | --- | --- | --- | --- |
| OpenWeather Ltd. (info@openweathermap.org) | 영국 | 대략적인 위치, IP 주소 | 날씨를 조회할 때 인터넷(HTTPS)으로 전송 | 날씨 예보 조회 | 해당 업체 방침에 따름 |
| Google LLC (<https://support.google.com/policies/contact/general_privacy_form>) | 미국 | 광고 ID, IP 주소, 기기 정보 등 | 광고 표시와 공지 조회 때 인터넷(HTTPS)으로 전송 | 광고 표시, 공지사항 제공 | 해당 업체 방침에 따름 |
| Discord Inc. (privacy@discord.com) | 미국 | 피드백 글, IP 주소 | 피드백을 보낼 때 인터넷(HTTPS)으로 전송 | 피드백 전달 | 4항의 피드백 보관 기간 |

이전을 원하지 않으면 아래 방법으로 거부할 수 있습니다.

- 날씨 조회: 위치 권한을 허용하지 않으면 됩니다. 이 경우 비 예보 알림을 받을 수 없습니다.
- 피드백: 피드백을 보내지 않으면 됩니다.
- 광고 ID: 6항의 방법으로 삭제할 수 있습니다.
- 광고 표시와 공지 조회에 따른 접속 정보(IP 주소 등): 앱을 사용하는 동안 전송되므로, 원하지 않으면 앱 사용을 중단하고 앱을 삭제해 주세요.

### 4. 보관과 삭제

- 앱이 기기에 저장한 정보는 앱을 삭제하면 모두 지워집니다.
- 설정 > "모든 데이터 초기화"로 루틴, 소지품, 기록, 마지막 위치 등 앱 데이터를 지울 수 있습니다. 초기화 후 앱을 다시 열면 위치 권한이 허용된 경우 새 위치가 저장됩니다.
- 마지막 위치는 새 위치를 받을 때마다 덮어쓰고, 1개만 보관합니다.
- 앱은 기기 백업에 데이터를 포함하지 않습니다.
- 피드백은 작성자를 알 수 있는 정보 없이 전송되어, 개발자는 누가 보냈는지 알 수 없습니다. 피드백은 앱을 운영하는 동안 보관하고, 앱 운영을 종료하면 파기합니다.
- 보낸 피드백의 삭제를 원하면 보낸 내용과 시기를 알려 주세요. 해당 피드백을 찾을 수 있으면 지체 없이 삭제합니다.

### 5. 안전성 확보 조치

- 외부 서비스와 주고받는 정보는 HTTPS로 암호화해 전송합니다.
- 기기에 저장하는 정보는 앱 전용 저장 공간에 보관하고, 기기 백업에 포함하지 않습니다.
- 정확한 위치를 요청하지 않는 등 기능에 필요한 최소한의 권한과 정보만 사용합니다.

### 6. 광고 ID (자동 수집 장치)

앱은 광고를 표시하기 위해 Google AdMob을 사용하며, 이 과정에서 광고 ID가 자동으로 수집될 수 있습니다. 앱은 비개인화 광고만 요청합니다. 광고 ID는 기기의 설정 > 개인정보 보호 > 광고 > "광고 ID 삭제"에서 지울 수 있습니다 (기기에 따라 메뉴 이름이 다를 수 있습니다).

### 7. 권한

| 권한                 | 용도             | 거부하면                         |
| -------------------- | ---------------- | -------------------------------- |
| 위치 (대략적인 위치) | 비 예보 확인     | 비 예보 알림을 받을 수 없음      |
| 신체 활동            | 외출 감지        | 외출 감지와 알림이 동작하지 않음 |
| 알림                 | 우산·소지품 알림 | 알림을 받을 수 없음              |

권한은 언제든지 기기 설정 또는 앱의 설정 화면에서 바꿀 수 있습니다.

### 8. 이용자의 권리

앱은 정보를 기기 안에 저장하고 개발자 서버로 보내지 않기 때문에, 이용자는 앱 데이터 초기화나 앱 삭제로 직접 정보를 지울 수 있습니다. 피드백 삭제(4항 참고)를 원하거나 개인정보 관련 문의가 있으면 아래 연락처로 알려 주세요.

### 9. 아동

앱은 만 14세 미만 아동을 대상으로 하지 않으며, 아동의 개인정보를 알면서 수집하지 않습니다.

### 10. 개인정보 보호책임자

- 이름: 이준형
- 이메일: dkflfdj@gmail.com
- 전화: 010-2793-0869

### 11. 권익 침해 구제

개인정보 침해에 대한 신고나 상담은 아래 기관에 문의할 수 있습니다.

- 개인정보침해신고센터: (국번 없이) 118, <https://privacy.kisa.or.kr>
- 개인정보분쟁조정위원회: 1833-6972, <https://www.kopico.go.kr>
- 대검찰청 사이버수사과: (국번 없이) 1301
- 경찰청 사이버수사국: (국번 없이) 182

### 12. 방침 변경

이 방침이 바뀌면 이 페이지에 바뀐 내용과 시행일을 게시합니다. 이전 버전은 [변경 이력](https://github.com/FactoryForLee/umbi-privacy/commits/main/index.md)에서 확인할 수 있습니다.

| 시행일 | 변경 내용 |
| --- | --- |
| 2026년 11월 18일 | 백그라운드 위치 사용 안내, 국외 이전 상세 내용, 피드백 보관 기간, 안전성 확보 조치, 광고 ID 안내 추가. 초기화 범위에 마지막 위치 추가. 연락처 이메일 변경 |
| 2026년 11월 3일 | 최초 시행 |

---

# English

## UmBi Privacy Policy

UmBi ("the app") reminds you about rain and the items you need when you head out. The app has no sign-up or login, and the developer does not run any server. This policy explains what information the app handles and how.

- First effective: 2026-11-03
- Last revised and effective: 2026-11-18

### 1. Information we handle and why

| Information                                            | Purpose                                     | Where it goes                                                                                         |
| ------------------------------------------------------ | ------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Approximate location (latitude, longitude)             | Checking the rain forecast where you are    | Sent to OpenWeather when checking the weather. The last location is kept on your device as a fallback |
| Physical activity (walking / still)                    | Detecting when you head out                 | Used only on your device, never sent anywhere                                                         |
| Routine times, item lists, daily records, app settings | Providing app features                      | Stored only on your device                                                                            |
| Feedback you write                                     | Reading your feedback and improving the app | Sent to the developer's Discord channel                                                               |

- The app never asks for your precise (GPS-level) location. It uses approximate location only.
- While the sensor is on, the app checks your location when it detects you heading out, even if the app is closed (a persistent notification is shown), to look up the rain forecast. It also updates the last location when you open the app. Turning the sensor off stops background location checks.
- The app does not collect your name, phone number, or email address.
- Only the text you write is sent as feedback. No device or account information is sent with it, although your IP address reaches Discord as part of the connection. Please do not include personal information in your feedback.

### 2. Third-party services

The app uses the services below. Each service handles information under its own privacy policy.

| Service                                    | Information shared                                        | Purpose                                 | Policy                                        |
| ------------------------------------------ | --------------------------------------------------------- | --------------------------------------- | --------------------------------------------- |
| OpenWeather (OpenWeather Ltd., UK)         | Approximate location (latitude, longitude), IP address    | Weather forecast                        | <https://openweather.co.uk/privacy-policy>    |
| Google AdMob (Google LLC, USA)             | Advertising ID, IP address, device information, etc.      | Showing ads (non-personalized ads only) | <https://policies.google.com/privacy>         |
| Firebase Cloud Firestore (Google LLC, USA) | Connection information such as IP address                 | Loading announcements (read only)       | <https://firebase.google.com/support/privacy> |
| Discord (Discord Inc., USA)                | Feedback text you write, IP address                       | Delivering feedback                     | <https://discord.com/privacy>                 |

### 3. International transfers

Information is transferred abroad as shown below, to the extent needed to provide the app's features. The legal basis is processing necessary to provide the app (performance of the service agreement), disclosed in this policy (Article 28-8(1)(3) of the Korean Personal Information Protection Act).

| Recipient (contact) | Country | Information | When and how | Purpose | Retention |
| --- | --- | --- | --- | --- | --- |
| OpenWeather Ltd. (info@openweathermap.org) | UK | Approximate location, IP address | Over HTTPS when checking the weather | Weather forecast | Per the company's own policy |
| Google LLC (<https://support.google.com/policies/contact/general_privacy_form>) | USA | Advertising ID, IP address, device information, etc. | Over HTTPS when showing ads or loading announcements | Showing ads, announcements | Per the company's own policy |
| Discord Inc. (privacy@discord.com) | USA | Feedback text, IP address | Over HTTPS when you send feedback | Delivering feedback | See feedback retention in section 4 |

If you do not want this, you can refuse as follows.

- Weather: deny the location permission. You will not get rain alerts.
- Feedback: do not send feedback.
- Advertising ID: delete it as described in section 6.
- Connection information for ads and announcements (such as IP address): this is sent while you use the app. If you do not want this, stop using and uninstall the app.

### 4. Retention and deletion

- Everything the app stores on your device is deleted when you uninstall the app.
- Settings > "Reset all data" deletes app data such as routines, items, records, and the last location. If location permission is granted, a new location is saved the next time you open the app.
- Only one last location is kept, and it is overwritten each time a new location is received.
- The app does not include its data in device backups.
- Feedback is sent without any information that identifies the sender, so the developer cannot tell who sent it. It is kept while the app is in operation and destroyed when the app is discontinued.
- If you want feedback you sent to be deleted, tell us what you wrote and roughly when you sent it. If we can find it, we will delete it without delay.

### 5. Security

- Information exchanged with external services is encrypted in transit using HTTPS.
- Information stored on your device is kept in the app's private storage and excluded from device backups.
- The app uses only the permissions and information its features need. For example, it never requests precise location.

### 6. Advertising ID

The app uses Google AdMob to show ads, and your advertising ID may be collected automatically in the process. The app requests non-personalized ads only. You can delete your advertising ID in your device settings under Privacy > Ads > "Delete advertising ID" (menu names may vary by device).

### 7. Permissions

| Permission             | Used for                    | If denied                               |
| ---------------------- | --------------------------- | --------------------------------------- |
| Location (approximate) | Checking the rain forecast  | No rain alerts                          |
| Physical activity      | Detecting when you head out | Outing detection and alerts do not work |
| Notifications          | Umbrella and item reminders | No reminders                            |

You can change permissions at any time in your device settings or in the app's settings screen.

### 8. Your rights

The app keeps your information on your device and does not send it to a developer server, so you can delete it yourself by resetting the app data or uninstalling the app. If you want feedback deleted (see section 4) or have any privacy questions, contact us below.

### 9. Children

The app is not directed at children under 14, and we do not knowingly collect personal information from children.

### 10. Contact

- Name: JunHyeong Lee
- Email: dkflfdj@gmail.com
- Phone: +82 10-2793-0869

### 11. Changes

If this policy changes, the updated policy and its effective date will be posted on this page. Earlier versions are available in the [change history](https://github.com/FactoryForLee/umbi-privacy/commits/main/index.md).

| Effective date | Changes |
| --- | --- |
| 2026-11-18 | Added background location use, international transfer details, feedback retention, security measures, and advertising ID information. Added the last location to what a reset deletes. Changed the contact email |
| 2026-11-03 | First version |
