# WEB - HTML
- [WEB1](https://www.opentutorials.org/course/3084)

본 강의를 통해 HTML을 학습하고 VSC를 사용하여 실습한 내용입니다.

---
## 1. 기본 문법 - 태그
바탕화면에 **WEB** 디렉터리 생성 후 VSC로 열기

- *1.html* 파일 생성 후 텍스트 입력   
```html
Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web applications.
```

- `<strong>` - 굵게 강조  
```html
Hypertext Markup Language (HTML) is the standard markup language for <strong>creating web pages</strong> and web applications.
```

- `<u>` - 밑줄 긋기
```html
Hypertext Markup Language (HTML) is the standard markup language for <strong>creating <u>web</u> pages</strong> and web applications.
```

- `<h1> ~ <h6>` - 제목 만들기 ※ 숫자가 커질수록 글씨는 작아진다.   
```html
<h1>HTML</h1>
Hypertext Markup Language (HTML) is the standard markup language for <strong>creating <u>web</u> pages</strong> and web applications.
```

- `<br> vs <p>` - 줄바꿈   

`<br>` 태그는 단지 줄바꿈이라는 시각적인 의미만 가지고 있기 때문에 닫는 태그가 없다.   
```html
ex...<br>ex...
```   
`<p>` 태그는 단락을 표현할 때 쓰며, 닫는 태그가 있다.     
```html
<p>ex...</p><p>ex...</p>
```

## 2. 부모 태그와 자식 태그   
태그가 서로 포함 관계에 있을 때 포함하고 있는 태그를 부모 태그, 포함된 태그를 자식 태그라 한다.
- `<li>` - 목차 또는 목록
```html
<li>1. HTML</li>
<li>2. CSS</li>
<li>3. JavaScript</li>
```

- `<li>` 태그의 부모 태그인 `<ul>` 태그 추가
```html
<ul>
  <li>1. HTML</li>
  <li>2. CSS</li>
  <li>3. JavaScript</li>
</ul>
```

- `<ul>` 태그를 `<ol>` 태그로 변경
```html
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>
```

- `<ul>` : unordered list, `<ol>` : ordered list

## 3. 문서의 구조
- `<title>` - 웹 페이지의 제목
```html
<title>WEB1 - html</title>
```

- `<meta>` - 웹 페이지에 대한 정보를 제공
  - utf-8로 웹 페이지를 열어라!
```html
<meta charset="utf-8">
```

- `<body>` 와 `<head>` 를 감싸는 `<html>`  

본문은 `<body>` 태그로 묶고, 본문을 설명하는 태그는 `<head>` 로 묶는다.   
그리고 이 둘을 `<html>` 태그로 감싼다.   
마지막으로 이 `<html>` 태그 위에 관용적으로 이 문서에는 HTML이 담겨 있다는 뜻에서 `<!DOCTYPE HTML>` 태그를 쓴다.
```html
<!doctype html>
<html>
  <head>
    <title>WEB1 - html</title>
    <meta charset="utf-8">
  </head>
  <body>
    <ol>
     <li>HTML</li>
     <li>CSS</li>
     <li>JavaScript</li>
    </ol>
    <h1>HTML</h1>
    ...생략...
  </body>  
</html>
```

## 4. `<img>` 태그와 속성
이미지를 웹 페이지에 포함시킬 때 사용하는 태그
- `<img>` 태그에 src 속성 추가   
  - 어떤 이미지인지 알려주도록 약속된 속성
```html
<img src="coding.jpg">
```

- `<img>` 태그에 width 속성 추가   
  - 이미지 크기 조절
```html
<img src="coding.jpg" width="100%">
```

## 5. `<a>` 태그와 속성
링크를 거는 태그. anchor의 약자. 
- `<a>` 태그에 href 속성 추가
  - href는 **H**yperText **Ref**erence의 약자
```html
<a href="https://www.w3.org/TR/html5/">Hypertext Markup Language (HTML)</a>
```

- `<a>` 태그에 target 속성 추가
  - 새 탭에서 열리게 해주는 속성
```html
<a href="https://www.w3.org/TR/html5/" target="_blank">Hypertext Markup Language (HTML)</a>
```

- `<a>` 태그에 title 속성 추가
  - 링크를 클릭하기 전에 툴팁을 표시해주는 속성
```html
<a href="https://www.w3.org/TR/html5/" target="_blank" title="HTML8 specification">Hypertext Markup Language (HTML)</a>
```

## 6. 클라이언트와 서버
![서버와 클라이언트3](https://github.com/skagn4929/HTML-start/assets/134206709/9523a0b4-e2d2-4a60-b458-eda02d3a5a36)

## 7. 기타 기능 추가
- [DISQUS](https://disqus.com/)   

댓글 기능 추가

- [TAWK](https://www.tawk.to/)   

채팅 기능 추가

---

## 결과물
- https://skagn4929.github.io/HTML-start/1.html

![web1](https://github.com/skagn4929/HTML-start/assets/134206709/58a1e2b5-4e29-4391-b2e7-87c3eef497e0)






