# 2023-1-OC-Web-Study
2023년 1학기에 진행된 OC 기초 웹 스터디 커리큘럼 과제 제출입니다.

## 🚩 지난 시간 복기해보자 🚩

- 서버와 리소스 -URI URN URL
- 리소스의 정체 - HTML, CSS, JS

  ▶ 이들로 사이트 생성 가능

  
- add 명령어; 지금 변경한 내용을 다음 커밋에 쓰겠다
- git directory = repository; 폴더에 .git이라는 폴더가 생김
- remote repository; 외부 저장소
- 깃허브; 파일 관리 서버; remote repository 中 1
- clone; 코드 옮겨오기(복사하기) (로컬로 작업하기 위해 깃허브 repository를 통해 로컬에 프로젝트 복사하는 것)

## 🌞 오늘은 뭘 배웠을까? 🌞


***

#### 🫧 브랜치가 뭘까❔
- 분기를 다룸
- 실체는 "포인터"; 가장 마지막 커밋을 가리키는 포인터
- $ git branch testing; testing 브랜치로 옮겨감
- $ git checkout testing; testing이라는 이름의 브랜치를 만듦
- $ git branch; 현재 있는 브랜치 모두 보기 가능

***

#### 💗 기본 협업 실습
1. 깃허브에서 레포 만들기

2. 폴더 하나 정해서 git clone 명령어로 클론

3. 받아서 브랜치 만들기

⚠️ 여기서 잠깐! 우리는 왜 협업할 때 branch를 나누어야 할까?
💨 각자의 작업에 서로 영향 주지 않고 독립적으로 진행하기 위함

; git branch <브랜치 이름>

; git branch => 브랜치 목록 띄워서 잘 만들어졌는지 확인, * 표시가 붙은 브랜치가 현재 브랜치

; git switch => 브랜치가 다른 브랜치에 있을 때 옮기기 가능

; git switch -c <새 브랜치 이름> => 현재 브랜치 기준으로 새 브랜치 생성할 때

4. 깃허브 사이트 메인 레포에서 add file 해서 아무 파일 만들기

5. git pull로 메인 브랜치에서 파일 받아오기

; git pull origin master 혹은 git pull origin main

***

#### 🦫병합(merge)하기
- 완성된 branch를 다른 branch로 병합하는 것
- 포인터 이동
- 더 일반적인 merge
- 공통 조상을 찾아 합침
- 3-ways merge 전략 

***
  
#### 🐇 행복한 리뷰 나누기 시간
- 팀원들의 리뷰 받기
; pull request(브랜치에서 완성된 작업을 master로 병합 요청하는 것) 생성 후 작업 내용에 comment 달기

- 코드 리뷰 하기
; pull request내의 files changed 탭에서 리뷰 가능

- 코드 리뷰 반영하기

***

#### 👻 fork란 무엇인고 하니!
- 다른 사람의 repository를 내 소유의 repository로 복사하는 것 
- fork한 repository를 기준으로 => 원본 remote(원래 소유자의 remote) : upstream, origin(내가 포크한 remote) : downstream
