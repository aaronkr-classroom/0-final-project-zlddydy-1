# Final Project Starter Files / 기말 프로젝트 시작 파일

This folder contains the starter files for the final project. You can use these files to start your project.<br>
이 폴더는 기말 프로젝트 시작 파일을 포함하고 있습니다. 이 파일들을 사용하여 프로젝트를 시작할 수 있습니다.

## Basic Requirements / 기본 요구사항

1. **Unit 4:** Build 3 models: `Subscriber`, `Transportation`, and `User`.<br>
   3개의 모델을 만드세요: `Subscriber`, `Transportation`, 그리고 `User`.
2. Build controllers for each model.<br>
   각 모델에 대한 컨트롤러를 만드세요.
3. Build views for each model.<br>
   각 모델에 대한 뷰를 만드세요.
4. Build CRUD routes for each model.<br>
   각 모델에 대한 CRUD 라우트를 만드세요.
5. Add one additional model, controller, and view (including CRUD routes) of your choice.<br>
   추가로 하나의 모델, 컨트롤러, 뷰 (CRUD 라우트 포함)를 만드세요.
6. **Unit 5:** Add User Authentication.<br>
   사용자 인증을 추가하세요.

## Bonus / 보너스

1. **Unit 6:** Build an API for one (or more) of your models.<br>
   모델 중 하나 (또는 그 이상)에 대한 API를 만드세요.
2. **Unit 7:** Add chat functionality to your app.<br>
   채팅 기능을 앱에 추가하세요.

### Included files / 포함된 파일

```bash
|___/views
| |___/partials               # <NEW>
| | |___header.ejs              # 모든 페이지에 사용되는 헤더
| | |___footer.ejs              # 모든 페이지에 사용되는 푸터
| | |___navigation.ejs          # 모든 페이지에 사용되는 네비게이션 바
| | |___confetti.ejs            # thanks.html에 사용되는 confetti
| |___layout.ejs              # <NEW> 모든 페이지의 레이아웃
| |___index.ejs                 # GET 메소드로 접근 가능
| |___transportation.ejs        # GET 메소드로 접근 가능
| |___contact.ejs               # GET과 POST 메소드로 접근 가능
| |___thanks.ejs                # POST 메소드 후에 접근 가능
| |___error.ejs                 # 에러 발생 시 접근 가능

|___/public                   # <NO CHANGES> 안 바뀜
| |___css
| | |___style.css
| | |___style.small.css         # 반응형 웹 디자인을 위한 CSS
| | |___bootstrap.min.css       # 부트스트랩 CSS
| | |___bootstrap.min.css.map   # 부트스트랩 CSS 맵
| | |___confetti.css            # thanks.html에 사용된 CSS
| |___img
| | |___dribbble_404.gif        # error.html에 사용된 이미지
| |___js
| | |___functions.js            # 반응형 메뉴를 위한 JS
| | |___bootstrap.bundle.min.js # 케러셀을 위한 부트스트랩 JS
| | |___bootstrap.bundle.min.js.map

|___/controllers              # <NEW>
| |___homeController.js         # 모든 라우트를 처리하는 컨트롤러
| |___errorController.js        # 모든 에러를 처리하는 컨트롤러

|___main.js                   # <NEW> Express 서버를 설정하는 파일
|___package.json              # <NEW> npm init을 통해 생성된 파일
|___package-lock.json
```