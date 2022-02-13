#<스터디 준비>

##그룹장분들이 repo 생성 후, 사용하시는 명령어
###1. 깃 시작 
    `git init`
###2. 깃허브와 연결하기
   `git remote add <upstream> <repo 주소>`
<upstream> 부분은 그룹장분들이 설정하고 싶은 명칭마다 다르게 설정하시면 될 것 같습니다!
제가 만든 repo는 upstream으로 설정하여 upstream으로 표기했습니다.
###3. 그룹원분들이 사용하실 branch 만들기
   `git branch <브랜치명>`
###4. 생성한 branch 목록 확인하기
   `git branch -v`
###5. branch 삭제하기
   `git branch -d <삭제할 브랜치명>`
###6. branch 이동하기
   `git switch <이동할 브랜치명>`
###7. 생성한 branch 깃허브에 올리기
   `git push <upstream>`


##그룹원분들이 repo를 fork 후, 사용하시는 명령어
###1. 깃 시작
아래의 명령어를 실행하면 `git init + 폴더 생성` 을 한번에 실행할 수 있습니다.
    `git clone <그룹원분들의 깃허브 계정에 생성된 스터디repo 주소> <생성할 폴더명>`
###2. 그룹원분들의 컴퓨터에 스터디용 repo를 등록하기
   `git remote -v`
   `git remote add <upstream> <repo주소>`
###3. 자신이 사용할 branch 이름 변경하기
   `git branch -m <현재 브랜치명> <변경할 브랜치명>`
###4. 자신이 사용할 branch로 이동하기
   `git switch <변경한 브랜치명>`





참고한 사이트
https://github.com/gwonihan/MulcamD_study/blob/master/Fork%20사용법.md


<스터디 진행> (미정)
`git fetch upstream`
파일 이름 : BOJ_문제번호_이름.py
`git add .`
`git commit -m "20220101"` 
`git push upstream`
