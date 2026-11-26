# 챙기자 개인정보처리방침

챙기자(Chaenggija, 일본어 이름 チェンギジャ, 패키지 `com.jtj.chaenggija`)의 한국어·영어·일본어 개인정보처리방침입니다. 개발자는 **JTJ**, 문의 주소는 **jtaejuwork@gmail.com**입니다. 문서 기준일은 **2026-11-26**입니다.

## 공개 주소

- 한국어 / Google Play Console 등록용: https://jtj91.github.io/jtj-privacy/
- 영어: https://jtj91.github.io/jtj-privacy/en.html
- 일본어: https://jtj91.github.io/jtj-privacy/ja.html
- 게시 저장소: https://github.com/JTJ91/jtj-privacy

정적 HTML과 CSS로 제공하며 로그인, JavaScript, 방문자 분석 도구, 외부 웹폰트가 없습니다. 호스팅 접속 요청은 GitHub Pages가 처리합니다.

## 방침에 포함한 처리

- 한 번만·반복 알림의 제목, 날짜·시각, 고정된 기준 시간대, 아이콘과 알람 설정의 기기 내 저장.
- 케이스 모양·색상과 충돌 진동 설정, 기기에서만 처리하는 가속도 센서 값.
- 반복 알림 완료·되돌리기의 최근 200건 기록, 개별 알림 삭제와 한 번만 알림 완료 시 삭제.
- AdMob의 IP 주소 기반 대략적인 위치, 앱 상호작용, 진단, 기기·계정 관련 식별자 처리와 광고·분석·부정행위 방지 목적.
- UMP의 지역별 개인정보 선택과 Android 광고 ID 설정, 광고 제거 구매 후 새 배너 요청 중단.
- Google Play 구매·서명된 영수증의 기기 내 검증과 복원. 앱은 카드번호나 결제 비밀번호를 받지 않음.
- Android 백업·기기 이전, 기기 데이터 삭제와 Google 보유 데이터 관리 방법.
- 사용자가 직접 보내는 지원 이메일과 첨부자료의 처리.

## 게시 파일과 앱 포함본

게시 대상은 `index.html`, `en.html`, `ja.html`, `styles.css`, `.nojekyll`, 이 `README.md`입니다. `main` 브랜치 루트에서 GitHub Pages로 배포합니다.

Android 앱 프로젝트의 `privacy-policy/`가 웹 게시용 원본입니다. 같은 HTML·CSS를 `app/src/main/assets/privacy/`에 복사하여 앱의 개인정보처리방침 화면에서 오프라인으로 표시합니다. 한국어는 `index.html`, 일본어는 `ja.html`, 영어와 그 외 언어는 `en.html`을 사용합니다. 각 문서의 상단과 하단에서 다른 언어로 이동할 수 있습니다. 앱의 문의하기는 주소와 제목이 설정된 메일 작성 화면만 열며 알림·영수증·로그를 자동 첨부하거나 메일을 자동 전송하지 않습니다.

HTML을 수정할 때는 웹 원본과 앱 포함본을 함께 갱신합니다. 공개 페이지 갱신은 기존 설치 앱의 내장 문서를 원격으로 바꾸지 않으며, 앱 포함본은 다음 앱 빌드에 반영됩니다.

## 운영상 확인 범위

Google 서비스의 보관 기간·처리 국가와 AdMob 콘솔 설정은 해당 서비스의 정책과 실제 설정에 따릅니다. 모든 데이터의 90일 내 자동 삭제나 개발자의 Google 데이터 원격 삭제를 약속하지 않습니다. Google Play 데이터 보안 양식은 광고 SDK의 처리까지 포함하여 실제 배포 버전과 일치시켜야 합니다.

## 공식 참고 자료

- [Google Play 사용자 데이터 정책](https://support.google.com/googleplay/android-developer/answer/10144311?hl=ko)
- [Google Mobile Ads SDK 데이터 안내](https://developers.google.com/admob/android/privacy/play-data-disclosure?hl=en)
- [GitHub Pages](https://docs.github.com/en/pages)

