# 크툴루의 부름 · 조사자 생성기 (Android)

index.html 을 WebView 로 감싼 안드로이드 앱 프로젝트입니다.

## 빌드 방법
1. Android Studio (Koala 이상)에서 이 폴더를 Open
2. Gradle Sync 완료 후 Run(▶)으로 기기/에뮬레이터에 설치
3. APK 만들기: Build > Build Bundle(s) / APK(s) > Build APK(s)

## 화면 수정
app/src/main/assets/index.html 을 교체/수정하면 앱에 그대로 반영됩니다.

## 참고
- 글꼴(Google Fonts)과 멀티플레이(PeerJS)는 인터넷 연결이 필요합니다. (INTERNET 권한 포함)
- 앱 ID: com.example.cocinvestigator (app/build.gradle.kts 에서 변경 가능)

## 설치용 APK 자동 빌드 (Android Studio 없이)
1. GitHub에서 새 저장소를 만들고 이 폴더의 모든 파일(.github 폴더 포함)을 업로드
2. 저장소의 Actions 탭 > Build APK 실행이 끝나길 기다림 (약 3~5분)
3. 완료된 실행 화면 맨 아래 Artifacts 의 CoC-Investigator-APK 를 받아 압축을 풀면 app-debug.apk
4. 폰으로 옮겨 열면 설치됨 (설정에서 "출처를 알 수 없는 앱 설치" 허용 필요)
