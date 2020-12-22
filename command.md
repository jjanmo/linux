# Basic Command

> 터미널에서 실행하는 모든 명령어는 **현재 내가 위치한 곳**에서 실행된다.

1. 그렇다면 **현재위치**는 어떻게 알 수 있을까?

pwd : 터미널에서의 현재위치를 알려준다
ls -al : 현재 위치의 디렉토리 안의 파일/디렉토리 리스트를 보여준다

mkdir :
touch :
ls
ls -a
ls -l

-rw-r--r-- 1 jjanmo staff 0 Nov 12 23:49 empty_file.txt
drwxr-xr-x 2 jjanmo staff 64 Nov 12 23:49 hello_linux

cd :
cd .. : : 상대경로
cd /home/ubuntu : /는 root : 절대경로

clear

rm hello_linux : X

> rm-r hello_linux : -r

rm empty_file

메뉴얼 찾아보는 방법

mkdir --help

> mkdir에 대한 간단한 사용방법을 볼 수 있다.

man ls

> 현재페이지를 벗어나서 ls에 대한 상세한 사용설명서를 보여준다

sudo(super user do)

> 배경 : 유닉스 계열에서는 다중사용자 시스템 => 아무나 파일을 보고 수정하면 안되는 상황이 생김 => permission(권한)이라는 것을 부여하게 됨
> super user / root user

파일을 만들고 수정하는 방법(file edit / store)

> 편집기 : nano(beginner) / vi(vim)(intermediate/advanced)
