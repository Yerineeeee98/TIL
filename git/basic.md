# Git 기본 개념

## 분산버전 관리 시스템
- 클라이언트(우리 컴퓨터)와 서버(git 채널) 모두가 똑같은 데이터를 유지하여 버전을 관리하는 시스템

## 파일의 세가지 상태
-![git이미지](https://git-scm.com/book/ko/v2/images/areas.png) 
혹은 저장해서 쓸 때는 ../assets/git이미지.jpg

- 영역
  - working directory : 작성하고 있는 코드, 파일
  - staging area : add 명령어로 무대 위로 올라간 파일들 (git에 저장되기 전의 파일)
  - git directory(repository) : commit 명령어로 찍힌 스냅샵들을 저장 (git에 올라간 파일)

- code .gitconfig 에서 아이디랑 이름 변경 가능

## 파일의 라이프 사이클
![lifecycle](../assets/lifecycle.png)
- tracked (관리대상임) ,untracked(관리대상이 아님, 파일을 새로 만든 상태)
   - tracked 파일: 이미 스냅샷에 포함돼 있던 파일이다. 
        - Unmodified(수정하지 않음),  Modified(수정함), Staged(커밋으로 저장소에 기록할) 
    - Untracked : 워킹 디렉토리에 있는 파일 중 스냅샷에도 Staging Area에도 포함되지 않은 파일이다.
