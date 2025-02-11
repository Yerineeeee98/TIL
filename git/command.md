# 명령어 정리

## git init
- 현재 디렉토리에 `.git` 폴더를 생성하여 새로운 GIT 저장소를 초기화.

## `git clone` 
- 내 폴더를 복사해서 다른 폴더 or 컴퓨터에 저장, 뒤에 내가 원하는 파일의 주소를 입력

```
git clone {remote_url} https://github.com/Yerineeeee98/TIL.git(내 til 폴더를 저장하려면  url에 til 폴더 주소 입력)
git clone {remote_url} {directory_name} -다른 이름으로 저장
```
## `git status`
 - 현재 git 상태를 확인
   - tracked, untracked 파일을 구분하여 표시
 ## `git add`
  - working directory에서 변경된 파일을 staging area에 이동

```
git add {file_name/directory_name}
git add . => 현재 나의 위치를 기준으로 모든 파일과 폴더
```

## `git commit`
- staging area에 있는 변경사항을 커밋하여 스냅샷 생성



