# 3장. CSS 개요

- CSS 기본 사용법과 셀렉터 알아보기


## CSS3 스타일 시트
- CSS(Cascading Style Sheet)
  - CSS로 작성된 코드를 스타일 시트(style sheet)라고 부름
  - HTML 문서의 색이나 모양 등 외관을 꾸미는 언어
    - 디자인, 레이아웃 및 다양한 장치 및 화면 크기에 대한 디스플레이의 변형을 포함하여 웹 페이지의 스타일을 정의하는 데 사용
  - 현재 CSS3: CSS level3
    - CSS1 -> CSS2 -> CSS3 -> CSS4(현재 표준화 작업 중)
  - https://www.w3schools.com/css

## HTML문서에 CSS3 스타일 시트 만들기
- HTML문서에 CSS3 스타일 시트 만드는 법 3가지
  - 인라인 스타일(inline style)
    - 태그의 style 속성으로 사용
  - 내부 스타일 시트(Internal style sheet)
    - `<style>` ... `</style>`
  - 외부 스타일 시트(External style sheet)
    - `<link rel="stylesheet" type="text/css" href="03.css">`
- CSS 적용 우선순위
  - 인라인 스타일
  - 내부 스타일 시트에 적용된 스타일
  - link를 통해 외부 스타일 시트 파일에서 적용한 스타일

## 인라인스타일
- HTML 태그에 style 속성을 사용

## 내부 스타일 시트
- `<style>` 태그를 이용하여 HTML 내부에 작성
  - 주로 `<head>` 태그에 작성

## 외부 스타일 시트

## CSS의 구성
- 셀렉터(selector)
  - 스타일을 고칠 HTML 요소
  - 고칠 스타일은 여러 개의 선언으로 지정가능
  - 반드시 {}로 묶어야 함

- 선언(declaration)
  - 콜론(:)으로 구분된 CSS속성 이름과 값이 포함
  - 세미콜론(;)으로 끝남

## 셀렉터의 종류
- 요소 셀렉터(Element Selector)
  - HTML 요소 이름을 기반으로 요소 선택
  - HTML 태그 이름 사용
  - 예) section {...}
  - *는 전체 요소 지정
- 클래스 셀렉터(Class Selector)
  - class 속성을 가진 요소를 선택
  - 마침표(.) 다음에 class속성의 값 사용
  - 예) .c1 {...}
- 아이디 셀렉터(ID Selector)
  - id 속성을 가진 요소를 선택
  - 해시(#) 다음에 id속성의 값 사용
  - 예) #s1 {...}

## 박스 모델(Box Model)
- HTML 요소의 실제 내용(Content), 패딩(Padding), 테두리(Border), 여백(Margin)으로 구성

## 여백 지정
- 안쪽 여백(Padding)
  - padding 속성으로 지정
  - 각 면에 대하여 지정
- 바깥쪽 여백
  - margin 속성으로 지정
  - 각 면에 대하여 지정

## 테두리 지정
- border
- border-style
- border-width
- border-color
- 각 면에 대하여 지정
  - 2개의 값 지정
  - 4개의 값 지정
