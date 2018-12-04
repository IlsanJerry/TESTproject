
#------------------------------------------------------------------------------#

 깃허브에 파일 올리는법 (일단 내가 아는 방법대로)

 1.mkdir ~/프로젝트명 (내 컴퓨터(로컬)내의 프로젝트파일 생성)
 2.cd ~/프로젝트명
 3.Github.com에서 레포짓(온라인 저장소만들기)
   ★로컬 프로젝트명과 온라인 프로젝트 이름이 동일해야함.

 4.깃허브(온라인저장소)와 로컬(내컴퓨터내의 프로젝트)를
  연결해야함 
 4-1.git config --global user.name"깃허브 계정 이름"
 4-2.git config --global user.email"깃허브 계정 이메일"
 4-3.git remote add origin https://github.com/IlsanJerry/TESTproject.git
 4-4.git remote -v (연결이 됬는지 확인)

 5. 계정 연결은 끝남 .
 6.git init (초기화..?)

 7. 로컬저장소에 올리거나 작업할 파일들 올려놓기
 8. git status로 상태 확인 ("붉은 글씨로 untracked로 뜸)

 9. git add [untracked 상태의 파일명] Ex) git add BaseballFinal.Rmd
10. git commit -m "[tracked된 파일명]"  Ex)git commit -m "Baseball_Final.Rmd"

11. git push -u origin master (이렇게 치면 이제 온라인저장소에 등록 완료)

끗..ㅇㅇ; 18년 12월4일 스타벅스서 많은 삽질 끝에 성공함.. ㅜ 


#------------------------------------------------------------------------------#