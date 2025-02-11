# 명령어 정리

## git init
- 현재 디렉토리에 `.git` 폴더를 생성하여 새로운 GIT 저장소를 초기화.
- 만약 다른 장소에 잘못만들었다면 rm -r .git하기 (다른 장소의 폴더로 이동해서)

## `git clone` 
- 내가 원하는 폴더를 복사해서 다른 폴더 or 다른 컴퓨터에 저장, 뒤에 내가 원하는 파일의 주소를 입력

```
git clone {remote_url} https://github.com/Yerineeeee98/TIL.git(내 til 폴더를 저장하려면  url에 til 폴더 주소 입력)
git clone {remote_url} {directory_name} -다른 이름으로 저장
```
## `git status`
 - 현재 git 상태를 확인 (git 파일이 위치한 폴더로 이동해서 해야함, til 폴더의 git파일을 확인하고 싶다면 til폴더까지 이동, py 폴더의 git파일을 확인하고 싶다면 py폴더로 이동)
   - tracked, untracked 파일을 구분하여 표시

   
 ## `git add`
  - working directory에서 변경된 파일을 staging area에 이동

```
git add {file_name/directory_name}
git add . => 현재 나의 위치를 기준으로 모든 파일과 폴더
```

## `git commit`
- staging area에 있는 변경사항을 커밋하여 스냅샷 생성
```
git commit -m "제목"
```


## `git log`
  -커밋의 히스토리를 조회 (종료는 wq입력)
   - option
     - `--oneline`
     - `--graph`


## `git remote``
-원격저장소 관리 명령어
 - option
   
  - 원격 저장소 확인
  ```
  git remote -v
  ```
  - 원격저장소 추가
    - 일반적으로 remote_name은 `origin` 사용
  ```
  git remote add {remote_name} {remote_url}
 ```
 - 원격저장소 삭제
 ```
 git remote remove {remote_name}
 ```

## git pull
- 원격저장소 커밋을 다운로드
```
git pull {remote_name}{branch_name}
```