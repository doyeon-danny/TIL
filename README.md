$git add helloworld.py  >  stage area에 올라감 (add : commit  할 목록에 추가)

$git commit -m  > -로 시작하면 보통 short name 옵션 

$git config --global user.name "John"

cli vs gui
Command Line Interface : Mouse 없이 코드로 조작하는 방법

pwd

ls

clear, ctrl+L

touch a.txt > 파일 만드는 법

mkdir test > 폴더 만드는 법

rm a.txt > 만든 파일 지우기

rm -r test > 만든 폴더 지우기

cd /   > 최하단의 위치로 이동

cd ~  > 홈 디렉토리로 이동

cd videos/   > videos 폴더로 이동

cd ..   > 상위 폴더로 이동(뒤로 가기)

cd -   > 바로 전에 있던 위치로 이동

cd ../..   > 상위 폴더 두 번 이동

git config --global user.name doyeon.danny

git config --global user.mail doyeon.danny@gmail.com

git config --global --list  > global의 리스트 보기

git init   > (master)라는 메인 브랜치 생성 = git의 관리를 받고 있다

git status  >  안올라갔으면 빨간색으로 파일명 뜸

git add a.py

git commit -m "first commit"

git status (아무것도 없음, a.py는 이미 등록되어 있어서)

git log   > commit 한 기록 보여줌

 변경 후

git status  > 다시 빨간색으로 변경사항 뜸

git add a.py  > 다시 등록

git status  > modified

git commit -m "second commit"

git status

git b.py

touch .gitignore  > 정보공개를 원하지 않는 비밀 파일 생성
	이 안에 b.py 를 입력

git status   > b.py는 숨김처리 되어 빨간색으로 안뜬다

git add .  > 모든 파일 한번에 등록

*검색어 입력창에 . 이 있을 때 : q (quit)를 눌러 해결

SSAFY 자료는 TIL에 올리면 안됨.

TIL - 수업 외적인 공부(public)

lectures - 수업내용 정리(private) 