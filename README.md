# Day3_mission
- - -
## 김현아입니다. 

* 오늘의 과제 1: 기본 세팅
  * 1번: 깃허브에서 새 레파지토리(Day3mission)을 만듭니다.
  * 2번: 내가 동기화하고 싶은 폴더에서 README.md 파일을 만듭니다.
  * 3번: 터미널 도구(warp)에서 내가 동기화하고 싶은 폴더에 접속한 후 git init(버전 관리 시작)을 선언합니다.
  * 4번: git add README.md 명령어를 통해 리드미파일을 버전 관리 대상으로 삼습니다.
  * 5번: git commit -m "first commit" 명령어를 통해 첫 커밋을 등록합니다. (기본값)
  * 6번: git branch -M main 명령어를 통해 해당 폴더를 메인 브랜치화합니다. (기본값/M=강제의 의미, master인 경우가 많아서)
  * 7번: git remote add origin [새 레파지토리 주소]인 명령어를 입력합니다. (그럼 이 폴더는 새 레파지토리 주소를 바라보고 동기화 되게 됩니다.)  
  * 8번: git push -u origin main 명령어를 입력해 내 컴퓨터의 메인 브랜치와 원격 서버의 main브랜치를 동기화하겠다고 선언합니다. 

* 오늘의 과제 2: 리드미 추가 작업 / 새 브랜치 업로드
  * 9번: git status로 내 위치를 확인합니다. (내가 기준으로 삼을 브랜치에 와 있는지 확인합니다)
  * 10번: git branch 브랜치명을 통해 새 브랜치를 생성합니다.
  * 11번: git checkout 9번에서 만든 브랜치명을 입력해 이동합니다.
  * 12번: 3번에서 만든 README.md 파일을 파이참/VS Code 등으로 엽니다. 그리고 문서를 작성합니다.
  * 12번: git status > git add . > git commit -m "test:homework explain" 순으로 명령어를 입력합니다.
  * 13번: git push origin 9번에서 만든 브랜치명 명령어를 입력합니다.  
  * 14번: git 허브의 신규 브랜치에 접속한 상태에서 pull request를 눌러 문서를 작성합니다.  
  * 15번: 검토한 뒤에 메인 브랜치에 적용합니다?