# 안녕하세요.

1. git init : 저장소를 선언한다.
2. git add : 깃의 스테이징 영역에 파일을 추가한다.
3. git commit : 현재 스테이징의 내용을 하나의 스냅샷으로 저장한다.
4. git push origin main : 원본 레파지토리의 메인 브랜치에 현재 저장된 내용을 업로드한다.
----
## Git 명령어 및 사용법 정리
1. git init

    로컬 저장소에 git을 사용할 준비를 하는 과정.
    
    git init을 하게 되면 현재 폴더에 .git 이라는 폴더가 생성되며 해당 폴더에서 git 명령어를 사용할 수 있음.
2. git status

    파일에 수정 및 변경이 일어나면 해당 파일의 상태를 보여줌.
3. git add

    커밋하기 전 수정된 파일을 준비시킴.
    
    물건을 구매 전 장바구니에 담는 것과 유사.
    
    git add [파일명]=>특정 파일을 add
    
    git add .=>현재 폴더의 모든 파일을 add
4. git commit

    로컬 저장소에 변경된 파일을 commit함.
    
    git commit -m "msg"=>한 줄 메세지를 포함하여 커밋
    
    git commit=>여러 줄 커밋 메세지를 남기고 싶을 때 사용.
5. git log

    해당 명령어를 통해 커밋된 파일의 히스토리 파악.
6. git remote

    원격 레포지토리를 로컬에 연결할 때 사용.
    
    git remote add origin [레포 주소]
    
    git remote --v=>현재 연동된 레포 정보를 확인.
    
    git remote update=>원격 레포에 등록된 브랜치를 전부 가져옴. (add origin만 할 경우 브랜치는 가져오지 않음.)
7. git push

    로컬 저장소에 커밋된 파일을 원격 저장소에 push(이미 원격 저장소가 생성되어 연동되어 있어야 함)
    
    git push [로컬 저장소 별칭][브랜치명]=>ex)git push origin master(현재는 main)
8. git clone

    로컬PC에 원격 저장소를 복사함
    
    git clone [레포 주소]
9. git branch=>현재 존재하는 브랜치 전부 조회

    git branch [브랜치명]=>새로운 브랜치 생성(브랜치를 생성해도 현재 브랜치에서 새로 생성한 브랜치로 이동하지 않기 때문에 별도로 이동해야함)
10. git switch

    브랜치 이동 명령어 git switch [브랜치명]
11. git pull

    특정 브랜치의 코드를 가져옴.

    git clone과의 차이점은 git pull은 특정 브랜치의 코드를 가져옴(내려받기). git clone은 원격 저장소 코드를 통째로 가져옴(복사하기).
    
    git pull [로컬저장소별칭][브랜치명]=>ex)git pull origin master(main)

12. git merge

    로컬에서 현재 브랜치와 특정 브랜치를 합침.

    git merge [브랜치명]

---
 -성환 : 오늘 한화가 이길까요 ?
 -성환 : 혹시 물개인가요 ?
    