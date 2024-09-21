# Algorithm Problem Solving

## 환경 세팅
### VSCode 설치
https://code.visualstudio.com/download

https://code.visualstudio.com/docs/cpp/config-mingw
### Github 연동
https://wikidocs.net/195273

`ctrl + shift + p`(or `F1`. i.e, command palette) -> `Git: Clone` -> `Clone from Github` -> repository 선택 -> local에 clone할 장소 선택(e.g., `C:\`)

테스트 파일 생성 -> VSCode 좌측 source control -> `+` 눌러서 변경 사항 staging -> `commit` -> `Sync Changes`(pull&push)

로그인 창 뜨면 ID & Personal Acess Token 입력

Github Token 발급 받는 방법: https://inpa.tistory.com/entry/GitHub-%F0%9F%8F%9B%EF%B8%8F-%EA%B9%83%ED%97%99-%ED%86%A0%ED%81%B0-%EB%B0%9B%EA%B8%B0

만약, 로그인 창이 안뜨고 아래와 같이 권한도 없다고 할 경우

`you don't have permission to push to "choiyhking/algorithm" on Github. Would you like to create a fork and push to it instead?`

https://gonpress.tistory.com/57

윈도우 검색: 자격 증명 관리 -> Windows 자격 증명 -> github 삭제 -> 다시 push 시도

**VSCode C++ 관련 설정**
Command Palette -> C/C++ Configurations
- Compiler path: C:/msys64/ucrt64/bin/g++.exe
- IntelliSense mode: windows-gcc-x64

테스트 cpp 코드 -> RUN -> C++(GDB/LLDB) -> C/C++: g++.exe... 클릭

만약 오류가 발생할 경우, `.vscode/task.json`에서 tasks.command.C:/msys64/ucrt64/bin/g++.exe 인지 확인

## 공부 방식
### 사용 언어
- C++
  - 기본 문법: https://youtu.be/UqCZda8DLGc?si=moCMYoCNTNZU7lmM
- Python
### 문제
- https://www.acmicpc.net/
- https://solved.ac/: `문제 > CLASS` 에서 순차적으로 풀기
