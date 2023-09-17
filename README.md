# vue-configuration

환경설정

### Chrome 설치


### node js 설치
https://nodejs.org 에서 LTS 버전 설치
---


### vue.js devtools 설치 (Chrome 확장팩)
  
https://chrome.google.com/webstore/detail/vuejs-devtools/iaajmlceplecbljialhhkmedjlpdblhp/related  <- 여기서 설치


-- https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd <- 여기 아님


---



### visual studio code 설치
https://code.visualstudio.com/

---

### extensions 설치
   1. vetur
   2. material icon
   3. night owl
   4. live server
   5. ESLint
   6. Prettier
   7. Auto Close Tag
   8. Atom Keymap

---

### extension 설정
  1. material icon
     mac :
       상단 code -> 기본 설정 -> 파일 아이콘 테마 -> material icon 설정
     window :
       상단 file -> preference -> theme -> file icon theme -> material icon 설정

  2. night owl
     mac :
       상단 code -> 기본 설정 -> 색테마 -> night owl 설정
     window :
       상단 file -> preference -> theme -> color theme -> night owl 설정

---

### Vue Cli 설치
1. npm install -g @vue/cli

Windows 환경에서
'vue : 이 시스템에서 스크립트를 실행할 수 없으므로 C:\Users\user\AppData\Roaming\npm\vue.ps1 파일을 로드할 수 없습니다. 자세한 내용은 about_Execution_Policies(https://go.microsoft.com/fwlink/?LinkID=135170)를 참조하십시오.' 
위와 같은 에러 발생시
https://hellcoding.tistory.com/entry/VSCode-%EC%98%A4%EB%A5%98-%EC%9D%B4-%EC%8B%9C%EC%8A%A4%ED%85%9C%EC%97%90%EC%84%9C-%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EB%A5%BC-%EC%8B%A4%ED%96%89%ED%95%A0-%EC%88%98-%EC%97%86%EC%9C%BC%EB%AF%80%EB%A1%9C
위 사이트 참조


---

### 참고

CLI 버전이 업데이트되면서 기본적으로 ESLint 오류가 나면 화면을 조작할 수 없게 되었습니다. ESLint 에러를 화면에 표시하지 않으려면 아래와 같이 설정해주세요.

1. 프로젝트 폴더에 `vue.config.js` 파일 생성

2. `vue.config.js` 파일에 아래 내용 입력

module.exports = {
  devServer: {
    overlay: false
  }
}
3. 파일 저장

4. `Ctrl + C`로 서버 종료 후 `npm run serve`로 다시 실행

5. 결과 확인

6. ---
