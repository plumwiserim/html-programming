# 2장 HTML 시맨틱 태그 

- HTML 시맨틱 태그 알아보기


## 시맨틱 웹(Semantic Web)
- 의미론적인 웹이라는 뜻
- 컴퓨터가 웹사이트를 단순한 코드의 구성이 아닌 의미를 가진 사이트라는 걸 알 수 있게 만드는 것
- HTML5 시맨틱태그(Semantic tag) 지원
  - 컴퓨터가 정보를 이해하고, 논리적인 추론까지 할 수 있는 구조를 만들기 위해 추가된 태그

## HTML5 시맨틱 태그(Semantic tag)
- `<header>`
  - 페이지나 섹션의 머리말 표현
  - 페이지 제목, 페이지를 소개하는 간단한 설명
- `<nav>`
  - 하이퍼링크들을 모아 놓은 특별한 섹션
  - 페이지 내 목차를 만드는 용도
- `<section>`
  - 문서의 장(chapter, section) 혹은 절을 구성하는 역할
  - 일반 문서에 여러 장이 있듯이 웹 페이지에 여러 `<section>` 가능
  - 제목태그(`<h1>`~`<h6>`)를 사용하여 절 혹은 섹션의 주제 기입
- `<article>`
  - 본문과 연관 있지만, 독립적인 콘텐트를 담는 영역
  - 혹은 보조 기사, 블로그 포스트, 댓글 등 기타 독립적인 내용
  - `<article>`에 담는 내용이 많은 경우 여러 `<section>` 둘 수 있음
- `<aside>`
  - 본문에서 약간 벗어난 노트나 팁
  - 신문, 잡지에서 주요 기사 옆 관련 기사, 삽입 어구로 표시된 논평 등 
  - 페이지의 오른쪽이나 왼쪽에 주로 배치
- `<footer>`
  - 꼬리말 영역, 주로 저자나 저작권 정보

## HTML 엔티티 코드(Entity Code)
- HTML에서 특수 문자를 쓸 때 사용

## 파일의 경로 
- 웹 페이지 작성시 하이퍼링크로 지정할 문서나 이미지, 외부 스타일 시트를 작성문서에서 지정할 때 해당 파일의 경로를 지정
- 경로지정방식
  - 절대경로: 내 컴퓨터 내에서 파일의 위치를 표시
  - 상대경로: 작업하고 있는 파일의 현재 위치를 기준으로 지정

## HTML 링크 - 책갈피
- 작성하고 있는 페이지의 특정 영역으로 이동하도록 작성
- `<a>` 태그의 id 속성을 이용하여 작성