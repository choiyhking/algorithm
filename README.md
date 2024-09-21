# Algorithm Problem Solving

## 환경 세팅

### VSCode 설치 및 Github 연동
https://code.visualstudio.com/docs/cpp/config-mingw
**C/C++ Configurations**
- Compiler path: C:/msys64/ucrt64/bin/g++.exe
- IntelliSense mode: windows-gcc-x64

RUN -> C++(GDB/LLDB) -> C/C++: g++.exe ~ 클릭
혹시나 안되면 .vscode/task.json에서 tasks.command.C:/msys64/ucrt64/bin/g++.exe 인지 확인
https://wikidocs.net/195273
ctrl + shift + p ( or f1) command palette -> Git: Clone -> Clone from Github -> repository 선택 -> local에 clone할 장소 선택(C:\)
좌측 source control -> + 눌러서 staging -> commit -> sync changes(pull&push)
로그인 창 뜨면 id & token 입력
https://inpa.tistory.com/entry/GitHub-%F0%9F%8F%9B%EF%B8%8F-%EA%B9%83%ED%97%99-%ED%86%A0%ED%81%B0-%EB%B0%9B%EA%B8%B0
로그인 창 안뜨고 권한도 없다고 뜨면
https://gonpress.tistory.com/57
자격 증명 관리 -> Windows 자격 증명 -> github 삭제

## 공부 방식
### 사용 언어
- C++
기본 문법: https://youtu.be/UqCZda8DLGc?si=moCMYoCNTNZU7lmM
- Python
### 문제
- https://www.acmicpc.net/
- https://solved.ac/: 문제 > CLASS 에서 순차적으로 풀기
