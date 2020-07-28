github 사용법
1. git 설치
2. git 설치 완료시 원하는 경로에 새 폴더 생성
3. 작업해온 내용 새 폴더로 이동

3.1 git 처음시작시 로그인 설정하기
3.1.1 git config --global user.email "you@example.com"

3.1.2 git config --global user.name "Your Name"


4. 새 폴더 위치에서 오른쪽 클릭 후 git bash 실행
5. git bash 창에서 git init 을 친다.
6. git bash 창에서 git add . 을 친다.  # 폴더내의 작업물 staging 에 저장
7. git bash 창에서 git commit -m "쏼라쏼라" # 새로 작업한 내용에 대한 코멘트 작성 및 local repo에 저장
8. git bash 창에서 git remote add origin (git clone url) # 깃허브 repo와 local repo 연결
8. git bash 창에서 git push -u origin master # 깃허브 repo에 작업물 업로드 완료
9. 위의 순서대로 해서 안되면 인터넷 찾아보기

p.s git이 깔려있으면 cmd창에서도 가능
