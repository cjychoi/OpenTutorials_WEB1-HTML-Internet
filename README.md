# OpenTutorials_WEB1-HTML-Internet
생활코딩 (opentutorials.org) WEB1 - HTML &amp; Internet Study

## 4. 코딩과 HTML
 - HTML: Hypertext Markup Language
 - 사람이 하는 일 (원인)
    - 코드 (code): 부호 또는 신호
    - 소스 (source): 원천
    - 언어: 약속
- 기계가 하는 일 (결과)
  - 애플리케이션 (=앱)
  - 응용 프로그램
  - 웹 페이지 < 웹 사이트 < 웹 애플리케이션
  
- HTML이 중요한 2가지 이유
  1. 쉽다.
  2. 매일 사용한다.
  
- 퍼블릭 도메인 (Public Domain)
  : 저작권이 없는 것
  - 예) 한글, 알파벳, 웹
  
## 5. HTML 코딩 실습 환경 준비
 - Atom 에디터 사용
 - 확장자는 .html
 - 자동 줄바꿈
   - preference -> editor -> Soft Wrap
   
## 6. 기본 문법 - 태그
 - `<strong> </strong>`: 진한 글씨
 - `<u> </u>` : 밑줄
 
 - 한글이 깨질 경우
   - `<meta charset="utf-8">`
   
## 7. 혁명적인 변화
 - `<h1> </h1>` ~ `<h6> </h6>` : 제목 (heading), 글자의 크기 및 두께 지정
 
## 8. 통계에 기반한 학습
 - [전 세계 웹페이지들에 가장 많이 사용된 태그 순위](https://www.advancedwebranking.com/html/)
 <p align="center"> 
   <img width="80%" src="https://user-images.githubusercontent.com/54846646/102689024-64b63380-423e-11eb-8514-e300a46b10b8.JPG" />
 </p>
 
## 9. 줄바꿈: br vs p
 - `<br>`: 새로운 줄 표현
   - 닫지 않는 태그
   - 원하는 만큼 간격을 줄 수 있음
 - `<p> </p>`: 단락 표현
   - 단락과 단락의 간격 고정 - 시작적 자유도가 떨어짐
   - CSS를 활용하여 간격 조정
     - `<p style = "margin-top:45px;">`: p 태그 위쪽에 45px 만큼의 여백(margin) 추가
 - 일반적으로 `<p>` 태그가 `<br>` 태그보다 좋은 선택 (84.3% vs 69.8%)
   - 단락의 경계를 분명히 하면서
   - CSS로 디자인 변경 가능
 
## 10. HTML이 중요한 이유
 - `<h3>coding</h3>` vs. `<strong><span style="font-size:22px;">coding</span></strong>`
   - 둘의 형태는 거의 비슷하지만,
   - 전자는 '제목'을 의미하지만, 후자는 '시각적인 장식'일 뿐.
   - 따라서 검색엔진은 전자의 형태로 된 페이지를 먼저 보여줄 것.
   
## 11. 최후의 문법 속성과 img
 - `<img src="coding.jpg" width="100%">`
 - 속성 (Attribute)
   - 태그의 이름만으로는 정보가 부족할 때 사용
   
## 12. 부모 자식과 목록
 - `<ul> </ul>` : Unordered list - `<li>` 태그의 부모 태그
 - `<ol> </ol>` : Ordered list - `<li>` 태그의 부모 태그
 - `<li> </li>` : list - `<ul> <ol>` 태그의 자식 태그
     
## 13. 문서의 구조와 슈퍼스타들
 - 사용 빈도수가 가장 높은 태그들
 - `<title> </title>` : 웹피이지의 제목
   - 검색엔진이 웹페이지를 분석할 때 가장 중요하게 생각
 - `<meta charset="utf-8">` : 한글 깨질 때 인코딩 읽기 방식을 지정해줌
 
 - `<head> </head>` : 본문을 설명하는 부분을 표시
 - `<body> </body>` : 본문을 표시 
 - `<doctype html>` : 관용적으로 html 문서 제일 위에 작성
 
 
## 14. HTML 태그의 제왕
 - `<a> </a>`: 링크 (Link), anchor 
   - `<a href="주소" target="_blank" title="html5 specification">` - 새 창에서 페이지 열림, 링크의 내용을 툴팁으로 보여줌
 
## 15. 웹사이트 완성
 - [완성된 결과물](https://web-n.github.io/web1_html_internet/index.html)
 
 
 
