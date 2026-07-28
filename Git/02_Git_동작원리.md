# Git 동작 원리

## Git의 전체 흐름

파일 수정
↓

파일 저장 (Cmd + S)
↓

git status
- 현재 Git 상태를 확인한다.

↓

git add .
- 변경사항을 Staging Area(커밋 준비 영역)에 추가한다.

↓

git status
- 커밋할 파일이 맞는지 다시 확인한다.

↓

git commit -m "메시지"
- Staging Area의 변경사항을 하나의 버전(Commit)으로 기록한다.

↓

git push
- Commit을 GitHub(원격 저장소)에 업로드한다.

---

# Git 명령어 정리

## git init

현재 폴더를 Git 프로젝트로 초기화한다.

📍 실행 위치
프로젝트 폴더

🔁 실행 횟수
프로젝트당 1회

---

## git status

현재 Git 프로젝트의 상태를 확인한다.

📍 실행 위치
프로젝트 폴더

🔁 실행 횟수
작업 중 수시로

---

## git add .

변경된 파일을 Staging Area에 추가하여 Commit 준비를 한다.

📍 실행 위치
프로젝트 폴더

🔁 실행 횟수
Commit 전마다

---

## git commit -m "메시지"

Staging Area의 변경사항을 하나의 버전(Commit)으로 기록한다.

📍 실행 위치
프로젝트 폴더

🔁 실행 횟수
작업이 끝날 때마다

---

## git push

Commit을 GitHub(origin)의 main 브랜치로 업로드한다.

📍 실행 위치
프로젝트 폴더

🔁 실행 횟수
Commit 후마다

---

# Git과 GitHub

Git
- 내 컴퓨터에서 버전을 관리하는 프로그램

GitHub
- Git 프로젝트를 저장하고 공유하는 원격 저장소

---

# 꼭 기억할 개념

- 저장(Cmd + S) ≠ Commit
- Commit ≠ Push
- Push를 해야 GitHub에서 확인할 수 있다.
- git add는 Commit할 변경사항을 선택하는 과정이다.
- git commit은 선택된 변경사항을 하나의 버전으로 기록한다.
- git push는 Commit을 GitHub에 업로드한다.

---

# 자주 사용하는 Git 명령어

git status

↓

git add .

↓

git status

↓

git commit -m "메시지"

↓

git push

---

# 오늘 배운 핵심

- Git은 파일 저장 프로그램이 아니라 버전 관리 프로그램이다.
- GitHub는 원격 저장소이다.
- 작업 흐름은 "수정 → 저장 → add → commit → push" 순서이다.
- add와 commit은 서로 다른 역할을 한다.
- Commit 후 파일을 수정했다면 다시 git add를 해야 새로운 변경사항이 Commit에 포함된다.