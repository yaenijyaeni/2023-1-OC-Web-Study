# 2023-1-OC-Web-Study
2023년 1학기에 진행된 OC 기초 웹 스터디 커리큘럼 과제 제출입니다.

## 🚩 지난 시간 복기해보자 🚩

git: 변경 사항 정리하고 협업을 조율

staging area 존재 => 한 줄로 git directory에 commit 가능

local repository: 변경사항, 관리할 것들 쌓여있음

협업을 하기 위해선 remote repository 필요

😶‍🌫️

commit message; 커밋 메시지 컨벤션에 따라 작성

브랜치: 가장 마지막 커밋을 가리키는 포인터
- $ git branch testing: testing이라는 이름의 브랜치를 만듦
- $ git checkout testing: testing 브랜치로 옮겨감
- $ git branch: 현재 있는 브랜치들 모두를 볼 수 있음

병합(merge); 3-ways merge: 공통 조상 찿아서 병합해줌

## 🌞 오늘은 뭘 배웠을까? 🌞

***

#### 🫧 HTML이 뭘까❔
HTML:Hyper Text Markup Language

💨 A문서 보다가 B문서 볼 수 있고, B문서 보다가 C, ... D ... => WEB 형성

HTTP: 인터넷 프로토콜

WWW(World Wide Web): 최초의 웹 사이트

***

#### 💗 HTML 기본 골격
태그
- html, head, title, h1 등 문서의 이름
- 열어 주면 닫아줘야 함
- 예외) br/ 줄바꿈 태그처럼 하나만 필요할 때도 있음

attribute
- 속성
- h1 style="color:red" 스타일이라는 속성을 정의해줌
- html Lang="en" 언어는 영어로 하겠음을 의미

4가지 구조
- !DOCTYPE htm> => Document Type : HTML. 문서에 대한 정보
- head => 화면에 잘 안 나옴. 컴퓨터(프로그램)에게 주는 정보가 적혀있는 곳. 문서의 특성을 정의해줌. 인코딩이나 웹 사이트 설명. 검색 엔진이나 시각 장애인에게 제공하는 프로그램에 자주 쓰임.
- body> => 웹사이트에 드러낼 정보
- html> => 시작과 끝을 명시

***

#### 🦫과제; 빙고 만들기
- 제목 - h1

; h1~h6: 강조하거나, 제목에 쓰이는 하이라이트 (수가 커질수록 글씨의 크기가 작아짐))
- 본문 - p 

; 한 문단을 의미
- 형광펜 - mark
- 중간 크기 볼드체 - b / strong
- 밑줄 - u
- 표

; table: table전체를 감싸는 태그

; tr: 테이블의 행을 의미하는 태그. 자손으로 th나 td가 반드시 있어야 함

; td:	테이블의 일반 셀(칸)을 의미하는 태그. 부모인 tr안에 있어야 함

- 입력칸

; input: input 태그는 닫기 태그가 없는 독립적인 태그

; input placeholder= ""/: 힌트를 표시, 내용을 입력하면 사라짐

예) 아이디를 입력하세요.

; label: 폼의 양식에 이름 붙이는 태그

주요 속성은 for로, label의 for의 값과 양식의 id의 값이 같으면 연결됨 ▶️ label을 클릭하면, 연결된 양식에 입력할 수 있도록 하거나, 체크를 하거나, 체크를 해제함
- 줄바꿈 - br/
