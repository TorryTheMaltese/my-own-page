# My Own Page

`제작목적` 챗 지피티를 이용해 쉽게 코딩, 사이트 제작 등의 시도를 할 수 있다는 것을 보여주기 위함

`기타사항` 업무관련 정보 사이트 제작을 생각했으나, 업무 관련 사항을 공개 사이트에 게시했다가 생기는 문제 등을 우려하여 개인 페이지로 노선 변경

### 제작

`html`, `(s)css`, `javascript`, `jquery`

템플릿: `html5up`-`Forty`

### 로그

```
2025-06-20 페이지 제작 시작
2025-06-23 템플릿 수정: 메인페이지 이미지 업로드 및 문구 수정
2025-07-04 템플릿 수정: 스타일 수정
2025-07-07 깃허브 웹페이지 호스팅, 페이지 문구 수정
2025-07-09 챗GPT 대화로그 업로드
```

### 챗 지피티 프롬프트 기록

#### 🌱 1단계: 아이디어

```plaintext
🙋‍♀️ 사용자: 챗GPT! 나 코딩을 전혀 모르는데, 나만의 웹사이트를 만들어보고 싶어. 가능할까?

🤖 ChatGPT: 물론이죠! HTML이라는 아주 간단한 언어로 시작할 수 있어요. 함께 만들어볼까요?
```

#### 🔧 2단계: 방법 제공 + 예제 코드

```plaintext
🙋‍♀️ 사용자: 좋아! 어떻게 시작하면 돼?

🤖 ChatGPT: 웹사이트는 보통 HTML, CSS, JavaScript라는 기술로 만들어져요.
우선 아주 기본적인 HTML 코드부터 볼까요?

html
<!DOCTYPE html>
<html>
  <head>
    <title>나의 첫 웹사이트</title>
  </head>
  <body>
    <h1>안녕하세요! 반가워요 :)</h1>
    <p>이건 내가 처음 만든 웹사이트야!</p>
  </body>
</html>
```

#### 🧰 3단계: 기술 간단 설명 + 도구 추천

```plaintext
🙋‍♀️ 사용자: HTML, CSS, JS가 정확히 뭔지는 잘 모르겠어…

🤖 ChatGPT:
- HTML은 뼈대예요. 어떤 내용이 있는지를 정해요.
- CSS는 꾸미기 담당! 글씨 색, 배경, 위치 등 스타일을 조절해요.
- JavaScript(JS)는 행동을 담당해요. 버튼을 누르면 뭐가 생기는 그런 거요.

코딩을 하려면 VS Code라는 무료 편집기를 쓰는 걸 추천해요!
또, Live Server라는 확장 프로그램을 쓰면 바로 결과를 확인할 수 있어요.
```

#### 🧪 4단계: 에러 발생 → 해결

```plaintext
🙋‍♀️ 사용자: 코드를 붙여넣었는데 화면에 아무것도 안 나와 ㅠㅠ

🤖 ChatGPT: 혹시 `index.html` 파일을 만들고 저장한 다음, Live Server로 열어봤나요?
또는 `<h1>`이나 `<body>` 태그에 오타는 없는지 확인해볼까요?
```

#### 🎨 5단계: 꾸미기 (CSS 활용)

```plaintext
🙋‍♀️ 사용자: 조금 더 예쁘게 꾸미고 싶은데, 어떻게 해야 해?

🤖 ChatGPT: CSS를 사용해볼게요! 아래처럼 글씨 색과 배경색을 넣을 수 있어요:

html
<style>
  body {
    background-color: #f9f9f9;
    font-family: 'Pretendard', sans-serif;
    color: #333;
    text-align: center;
  }
</style>
```

#### 🚀 **6단계: 사이트 배포하기 (GitHub Pages)**

```plaintext
🙋‍♀️ 사용자: 완성했어! 다른 사람들한테 보여주고 싶어!

🤖 ChatGPT: 깃허브(GitHub)를 이용하면 무료로 사이트를 배포할 수 있어요!
1. GitHub에 가입하고 새 repository를 만들어요.
2. index.html 파일을 업로드해요.
3. Settings > Pages로 들어가서 브랜치를 main으로 설정하고 저장하면,
   자동으로 주소가 생겨요! (예: https://yourid.github.io/yourrepo)
```
