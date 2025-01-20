# Git
## 실습
### git commit 실습

1. git_commit 폴더를 생성한 후 폴더 안에서 VScode 실행
2. git init 명령어를 실행
3. a.txt 파일을 만들기 위해 touch a.txt 명령어 실행
4. staging area로 옮겨주기 위해서 git add a.txt 명령어 실행
5. commit message로 commit을 생성하기 위해 git commit -m "add a.txt"실행
6. 중간 중간 git status를 실행하여 나의 진행 상태 파악하기.
7. git log를 통해 commit 목록을 확인하기.

- 로컬(local)
  - 현재 사용자가 직접 접속하고 있는 기기 또는 시스템 개인 컴퓨터, 노트북, 태블릿 등 사용자가 직접 조작하는 환경
- git 기타 명령어
  - git log --oneline : commit 목록을 한 줄로 보기. 핵심 정보만 나오게 된다.
  - git config --global -| : git global 설정 정보 보기
- 화면에서 (END)가 뜨게 되어 탈출이 안된다면 q를 입력해서 탈출이 가능하다.
- git 로컬 저장소 내에 또 다른 git 로컬 저장소를 만들지 말 것.

## Remote Repository
### Remote Repository
- 원격 저장소
  - 코드와 버전 관리 이력을 온라인 상의 특정 위치에 저장하여 여러 개발자가 협업하고 코드를 공유할 수 있는 저장 공간이다.