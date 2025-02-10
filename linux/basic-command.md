# 리눅스 기본 명령어

## 0. 명령어의 기본 형식
```
command [options] [arguments]
```
- **command 하고 띄어쓰기 매우 중요**
- coomand : 실행할 명령어, 프로그램
- options : 명령어의 옵션
- arguments : 명렁어에 전달할 인자 (데이터 값)
- ex ) python (command) -V (options)

## 1. 파일 및 디렉토리 관리

### ls : list  
- 디렉토리 내용 목록을 보여줌 ( 폴더는 /붙여서 파일은 /없이)
- options :
    - `l` : 파일의 상세 정보 표시
    - `a` : 숨김 파일 표시 (.으로 시작하는 파일은 모두 숨김파일로 표시됨)

### cd (change driectory)
- 현재 작업 디렉토리를 변경
- `cd {target-directory}`
  - target-directory는 자동완성 기능을 활용 (tab)
 
-`~` : 윈도우의 홈 느낌 

### pwd (print working directory)
- 현재 작업 중인 디렉토리의 전체 경로를 출력 (나의 현재 위치 확인)

### mkdire (make directory)
- 새로운 디렉토리를 생성
- `mkdir {directory-name}` 

### touch 
- 새로운 파일을 생성
- `touch {file-name}`

### rm (remove)
- 파일이나 폴더를 삭제
- options
  - `-r` : 디렉토리와 그 내용을 재귀적으로 삭제 

### cat (concatenate) 
- 파일의 내용을 출력 

 ### ctrl + l : 터미널 내용 지우기
