# selab-git-study

---

### ***필자는 sourcetree를 이용한 간단한 git사용법을 설명할 예정입니다.***

### INDEX

1. git이란?
2. git clone 방법
3. git branch 방법 
4. git commit 방법

## 1. Git이란?

---

Git은 버전 관리 시스템으로, 여러 명이 함께 작업할 때 파일의 변경 이력을 기록하고 관리할 수 있습니다. Git은 코드의 버전 관리뿐만 아니라 **협업**에 있어서도 매우 유용한 도구입니다.

<aside>
🌲 + Soucetree란?
Git을 보다 간편하게 이용할 수 있도록 도와주는 GUI 클라이언트입니다.
Git 명령어에 익숙하지 않더라도 간단한 인터페이스로 Git을 다룰 수 있게 해줍니다.

</aside>

## 2. git clone 방법

---

1. **내 컴퓨터로 가져오고 싶은 Github에 있는 `Code` 버튼을 눌러 URL을 복사해줍니다.** 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/28c430ef-f188-4a5c-9e75-931f4edaa710/Untitled.png)

1. **Sourcetree 실행 후 +버튼을 눌러 Clone 버튼을 눌러줍니다.**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d6f1d063-acb8-4eb6-ad01-d9b46570199f/Untitled.png)

1. `**소스 경로 / URL :` 에 복사한 URL을 넣어줍시다.**
    
    `**목적지 경로:` 는 자동으로 설정되며 원치않으면 변경이 가능합니다.**
    
    `**이름:` 은 프로젝트명(폴더명)입니다.**
    

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a74b4487-4517-4d1c-babe-b9b1b247ab2a/Untitled.png)

## 3. git branch 방법

---

천천히 잘 따라오셨다면 아래와 같은 상황일 겁니다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ed6a4708-bc5a-4455-b1b6-7243f249f58c/Untitled.png)

1. `브랜치` 버튼 눌러줍시다.
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6723334a-7169-4ac9-82d2-b8fa48ca2de0/Untitled.png)
    
2. `새 브린치:` 에 `본인 이름 / working` 적어줍시다. `브랜치 생성` 클릭

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7fe78413-8981-4601-b833-54916fb867c8/Untitled.png)

우와 브랜치가 생겼어요!

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f899467c-8b42-49ce-b2f1-a41e2f0a86d7/Untitled.png)

## 4. git commit 방법

---

이제 코딩을 ~~*휘뚜루마뚜루*~~ 마쳤으면 commit을 해서 파일을 원격 저장소에 저장해줍시다.

1. **커밋하지 않은 변경사항 눌러줍시다.**
2. `모두 스테이지에 올리기` 눌러줍시다. (스테이지에 올린다는 것은 커밋하기전에 커밋할 파일들을 선택하는 과정입니다.)
3. `커밋` 눌러줍시다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a85b9d69-091c-40bb-8e44-60c151cc8b1e/Untitled.png)

- 본인 닉네임 아래에 textfield가 있을텐데, 커밋 내용을 적어주는 부분입니다.
- READ.md를 수정했기 때문에 저는 `update README.md` 라고 적어줬습니다.

커밋 눌러줍시다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1315d4c9-76bb-43aa-b55e-95188423f177/Untitled.png)