# Mandarin Me 🇨🇳

개인 사용자를 위한 중국어 회화 코치 Android 앱 MVP입니다.

## 포함 기능
- 자유 대화 / 카페 / 식당 / 택시 / 친구 역할극
- 중국어 + 병음 + 한국어 힌트
- 사용한 중국어 표현 자동 저장
- 수준, 관심사, 집중 교정 영역 개인화
- 기기 로컬 학습 데이터 저장
- GitHub Actions APK 자동 빌드

## GitHub에서 APK 만들기
이 프로젝트의 **내용 전체**를 저장소 루트에 업로드하세요. `.github/workflows/android-apk.yml`도 반드시 포함해야 합니다.

업로드 후 `Actions > Build Android APK`가 자동 실행됩니다. 완료된 run의 **Artifacts > mandarin-me-apk**에서 ZIP을 받고 압축을 풀면 `app-debug.apk`가 있습니다.

## 로컬 실행
```bash
npm install
npx expo start
```

## 다음 개발 단계
현재 회화 응답은 오프라인 데모 엔진입니다. 다음 버전에서 실제 AI API, 음성 입력, 중국어 TTS, 자동 문법 교정, SRS 복습을 연결할 수 있습니다.
