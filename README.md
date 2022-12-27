보고서 폴더 만듦

숨김 항목 찾기 (.git)
-> git init
-> 버전 기록할 수 있음

ls -al (숨김 폴더 보임)

vsCODE 열기
-> 보고서.md

git status : 상태 보기

git add 보고소.md
git status -> Untrackted files : 트래킹 되지 않은 파일들
		1.txt를 만들었지만 add하지 않음
 
git commit -m '보고서'
git status -> Changes to be committed 
	: 보고서.txt 만들고 add함

git config --global user.email "lhj25846@naver.com"
git config --global user.name "hazziiss"
-> 덮어쓰기 가능

git log
: 버전 확인 명령어

Changes not staged for commit: 커밋을 위해 staged가 아닌 변경사항들
커밋된 적 있는 보고서.txt파일을 수정한 상태

