# **프로젝트 목적**
- Git 기반 협업을 위한 기본 환경을 구성
- 원격 저장소를 로컬로 클론하고, 개인 작업을 위한 브랜치를 생성하여 안전한 개발 흐름을 경험  
<br>

# **학습 내용 및 실행 방법**
## Git 시작 및 기본 설정
- git 저장소 시작 : git init
- commit 작성자 이름 설정 : git config user.name "이성준"
- commit 작성자 메일 설정 : git config user.eamil "l22blue@naver.com"
## 현재 상태 확인
- 현재 브랜치 및 파일 상태 확인 : git status
## 파일 생성 및 수정
- 빈 파일 생성 : touch 파일명.txt
- 파일을 터미널에서 수정 : nano 파일명.txt
## Git 파일을 관리 대상으로 등록
- 변경 파일 스테이징 : git add 파일명
## 변경 사항을 기록 
- 스테이징된 변경 사항 저장 : git commit -m "commit 메시지"
## commit 기록 확인
- commit 전체 기록 보기 : git log
- commit 요약 한 줄로 보기 : git log --oneline
- commit별 코드 변경까지 보기 : git log -p
## 브랜치 관리
- 브랜치 목록 확인 : git branch
- 새 브랜치 생성 : git branch 브랜치명
- 브랜치 이동 1 : git checkout 브랜치명
- 브랜치 이동 2 : git switch 브랜치명
## 과거 commmit으로 이동
- 특정 commit 시점으로 이동 : git checkout 커밋해시
## 작업 중인 변경 입시 보관
- 현재 작업 임시 저장 : git stash
- stash 목록 확인 : git stash list
- 임시 저장한 작업 다시 적용 : git stash pop
## 원격 저장소(github)로 업로드
- 처음은 push + upstream 설정 : git push -u 주소
- 이후는 간단하게 : git push
## 원격 저장소(github) 복제 (clone)
- 원격 레포지토리를 로컬로 복사 : git clone 주소
<br>

## cart 브랜치에서 이 줄만 수정했음