# electron_web

**자주 사용하는 웹사이트 하나를 앱으로 만들어 쓰자**
https://github.com/electron/electron-quick-start
여기에 webview 만 올렸음

## 원하는 사이트 설정하기
index.html 파일의 webview 태그 src 에 명시하면 끝

## 간단히 돌려보기
```
npm install
npm start
```

## 패키징 해서 쓰기
https://electronjs.org/docs/tutorial/application-distribution

mac 의 경우,
1.  [맥용 prebuild binary](https://github.com/electron/electron/releases/download/v4.0.5/electron-v4.0.5-darwin-x64.zip) 를 받아서 압축을 푼다.
2. `압축푼디렉토리/Electron.app/Contents/Resources/app/` 아래에 이 git 의 파일을 다 복사한다.
3. finder 에서 실행한다.
