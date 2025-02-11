## 헷갈리는 개념들

### git은 세가지 영역으로 나뉜다
> 영역
  - working directory : 작성하고 있는 코드, 파일
  - staging area : add 명령어로 무대 위로 올라간 파일들 (git에 저장되기 전의 파일)
  - git directory(repository) : commit 명령어로 찍힌 스냅샵들을 저장 (git에 올라간 파일) (.git 파일에 스냅샷)

마지막으로 push 명령어로 git hub에 저장됨

> 내가 현재 작성하는 파일에서 수정하거나 추가할 때 (저장 필수)

  1.   `git add .` 
  2. `git commit -m "파일이름"`
    - 게임의 세이브에 해당하는 행동으로 즉 변화한 부분을 저장하는 것을 의미
  3. `git push {origin} {master}`  

-1차 수정