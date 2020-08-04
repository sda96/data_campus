#github 사용법
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

#나만의 브랜치 만들기

 github 사용벙의 6단계까지 진행 후 (git commit -m "")
 
 git branch  (현재 branch 확인하기)
 
 git branch chang (chang이라는 이름의 branch 생성)
 
 git checkout chang (chang이라는 이름의 branch로 이동)

 git push -u origin chang 또는 git push -f origin chang
 
참고사이트 : 
1. https://backlog.com/git-tutorial/kr/stepup/stepup2_5.html, 
2. 허민석 유튜브 깃허브 강좌 영상
3. https://medium.com/@pks2974/%EC%9E%90%EC%A3%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EA%B8%B0%EC%B4%88-git-%EB%AA%85%EB%A0%B9%EC%96%B4-%EC%A0%95%EB%A6%AC%ED%95%98%EA%B8%B0-533b3689db81
4. https://git-scm.com/book/ko/v2/Git-%EB%B8%8C%EB%9E%9C%EC%B9%98-%EB%A6%AC%EB%AA%A8%ED%8A%B8-%EB%B8%8C%EB%9E%9C%EC%B9%98
5. https://wikim.tistory.com/201
