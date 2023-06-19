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

- 부모태그와 자식태그   

태그가 서로 포함 관계에 있을 때 포함하고 있는 태그를 부모 태그, 포함된 태그를 자식 태그라 한다.
  
1. `<li>` - 목차 또는 목록
```html
<li>1. HTML</li>
<li>2. CSS</li>
<li>3. JavaScript</li>
```
2. `<li>` 태그의 부모 태그인 `<ul>` 태그 추가
```html
<ul>
  <li>1. HTML</li>
  <li>2. CSS</li>
  <li>3. JavaScript</li>
</ul>
```
3. `<ul>` 태그를 `<ol>` 태그로 변경
```html
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ol>
```
※ `<ul>` : unordered list, `<ol>` : ordered list

## 2. `<img>` 태그와 속성
이미지를 웹 페이지에 포함시킬 때 사용하는 태그
- `<img>`태그에 src 속성 설정   
  - 어떤 이미지인지 알려주도록 약속된 속성
```html
<img src="coding.jpg">
```

- `<img>`태그에 width 속성 설정   
  - 이미지 크기 조절
```html
<img src="coding.jpg" width="100%">
```







