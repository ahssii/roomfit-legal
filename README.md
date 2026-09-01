# RoomFit 법적 문서

RoomFit 앱의 개인정보처리방침과 이용약관을 공개 URL로 제공하기 위한 저장소입니다.
App Store Connect와 Google Play Console은 등록 시 접속 가능한 개인정보처리방침 URL을
요구하므로, 앱 소스(비공개)와 분리해 이 문서만 공개합니다.

## 공개 주소

- 개인정보처리방침: https://ahssii.github.io/roomfit-legal/privacy-policy.html
- 이용약관: https://ahssii.github.io/roomfit-legal/terms-of-service.html

## 문서 수정 방법

GitHub 웹에서 파일을 열고 연필 아이콘을 눌러 바로 고칠 수 있습니다.
저장하면 몇 분 안에 위 주소에 반영됩니다.

**⚠️ 고칠 때 두 곳을 함께 맞춰주세요.**

1. 이 저장소의 `.md`와 `.html` (같은 내용의 두 형식)
2. **앱 저장소(`ahssii/room-filter`)의 `docs/` 안에 있는 같은 파일**

앱은 `docs/*.md`를 번들해서 설정 화면에서 그대로 보여줍니다. 즉 이 저장소만 고치면
**앱에 보이는 방침과 웹에 공개된 방침이 달라집니다.** 심사와 법적으로 문제가 될 수
있으니 반드시 양쪽을 같이 수정해야 합니다.

수정 후 두 저장소의 내용이 같은지 확인:

```bash
diff <(curl -s https://raw.githubusercontent.com/ahssii/roomfit-legal/main/privacy-policy.md) "docs/privacy-policy.md"
```
