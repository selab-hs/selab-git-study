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

![image1](https://user-images.githubusercontent.com/101298499/235932263-3cef7159-ef93-4ff6-8012-cca85d35d903.png)


1. **Sourcetree 실행 후 +버튼을 눌러 Clone 버튼을 눌러줍니다.**

![Untitled](https://user-images.githubusercontent.com/101298499/235932467-f5020939-77a7-4c5c-9c97-8ac1c17cc842.png)

1. `**소스 경로 / URL :` 에 복사한 URL을 넣어줍시다.**
    
    `**목적지 경로:` 는 자동으로 설정되며 원치않으면 변경이 가능합니다.**
    
    `**이름:` 은 프로젝트명(폴더명)입니다.**
    

![Untitled (1)](https://user-images.githubusercontent.com/101298499/235932479-9e5ec61f-05d3-4cae-ab6c-2bb6e3c4beb8.png)

## 3. git branch 방법

---

천천히 잘 따라오셨다면 아래와 같은 상황일 겁니다.

![Untitled (2)](https://user-images.githubusercontent.com/101298499/235932484-acd78f28-c964-4019-b2a2-23636f13dc6b.png)

1. `브랜치` 버튼 눌러줍시다.
    
![Untitled (3)](https://user-images.githubusercontent.com/101298499/235932489-9cdb9256-d80c-45db-9610-d34bf89a6920.png)

2. `새 브랜치:` 에 `본인 이름 / working` 적어줍시다. `브랜치 생성` 클릭

![Untitled (4)](https://user-images.githubusercontent.com/101298499/235932500-c342823d-a19a-4ce4-b2e7-158403950c5c.png)

우와 브랜치가 생겼어요!

![Untitled (5)](https://user-images.githubusercontent.com/101298499/235932512-d1f5d96a-00ba-45e9-9147-d6297aeefdcc.png)

## 4. git commit 방법

---

이제 코딩을 ~~*휘뚜루마뚜루*~~ 마쳤으면 commit을 해서 파일을 원격 저장소에 저장해줍시다.

1. **커밋하지 않은 변경사항 눌러줍시다.**
2. `모두 스테이지에 올리기` 눌러줍시다. (스테이지에 올린다는 것은 커밋하기전에 커밋할 파일들을 선택하는 과정입니다.)
3. `커밋` 눌러줍시다.

![Untitled (6)](https://user-images.githubusercontent.com/101298499/235932518-f8116f4d-ce01-4d31-ad9f-89e6f8a64781.png)

- 본인 닉네임 아래에 textfield가 있을텐데, 커밋 내용을 적어주는 부분입니다.
- READ.md를 수정했기 때문에 저는 `update README.md` 라고 적어줬습니다.

커밋 눌러줍시다.

![Untitled (7)](https://user-images.githubusercontent.com/101298499/235932524-6663974b-d585-4c5b-84f0-17b7bb2839e4.png)

커밋 성공

![Untitled (8)](https://user-images.githubusercontent.com/101298499/235932535-db11c7cb-9aca-414b-9568-fdddad42ffa1.png)

이런 방식으로 github 이용하시면 됩니다. 감사합니다.
