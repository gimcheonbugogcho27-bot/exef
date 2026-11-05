# 4-4반 SNS Windows 앱

이 프로젝트는 https://sns-ovgo.onrender.com/ 을 Windows 데스크톱 앱 창에서 실행하는 Electron 래퍼입니다.

## EXE 만들기

1. 이 폴더의 파일을 GitHub 저장소에 업로드합니다.
2. GitHub 저장소의 **Actions** 탭으로 이동합니다.
3. **Build Windows EXE** 워크플로를 선택하고 **Run workflow**를 누릅니다.
4. 빌드가 끝나면 실행 결과의 **Artifacts**에서 `4-4-sns-windows-installer`를 다운로드합니다.
5. ZIP을 풀고 `4-4반 SNS Setup 1.0.0.exe`를 실행해 설치합니다.

## 로컬 실행 (개발용)

```bash
npm install
npm start
```

## 참고

- 앱은 기존 웹사이트를 그대로 표시합니다. 게시물·채팅·시간표 데이터는 기존 서비스와 Supabase를 사용합니다.
- 인터넷 연결이 필요합니다.
- 로그인 상태는 앱의 로컬 저장소에 유지됩니다.
- Windows x64용 설치 파일을 생성합니다.
