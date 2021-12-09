[git 명령어 정리]

1. git add: git add 같은 경우 현재 작업하고 있는 디렉토리 내의 변경 사항을 unstaging 단계에서
                 staging 단계로 넘어가기 위해 사용하는 Git 명령어이다. 하나의 파일 add를 원하면  
                 git add "file name", 만약 전체 파일 add를 원하면 git add . 라고 해주면 된다

2. git commit: git commit 같은 경우 git add를 통해 staging 단계로 들어온 파일들을 내 local 
                       repository에 저장할 때 사용하는 Git 명령어이다. git commit -m "내용" 을 통해
                       메세지와 함께 내 local repository에 변경된 파일들을 저장할 수 있다

3. git push: git push 같은 경우 git commit을 통해 내 local repository에 저장된 파일들을 remote
                   repository, 즉 github에 연동시켜둔 내 원거리 저장소에 저장시키는 것이다. 
                   git push origin "branch name"을 통해 현재 local repository 내의 branch 내용을 
                   local repository의 해당 branch로 파일들을 저장시킬 수 있게 된다 
