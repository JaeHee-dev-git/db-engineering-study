# Git 기초 

## Git과 GitHub의 차이 

### Git

- 버전 관리 시스템
- 파일의 변경 이력을 관리한다.
- 이전 버전으로 되돌릴 수 있다 

### Git Hub

- Git 프로젝트를 저장하는 온라인 저장소
- 백업 및 협업에 사용한다. 

---

## Git 사용자 정보 등록 

### 사용자 이름 등록 
git config --global user.name "이름 작성"

### 사용자 이메일 등록 
git config --global user.email "Github 이메일 작성"

### 등록 확인
git config --global --list

---

## Repository 생성

Repository 이름 등록 
- public 
- README 생성 X 

---

## Git 프로젝트 시작 
git init  
- VScode에서 폴더를 열고, 터미널을 실행하여 현재 폴더를 Git 프로젝트로 등록!
- 프로젝트당 최초 1회 실행 

---

## 현재 상태 확인 
git status
- 새로운 파일 확인
- 수정된 파일 확인
- Commit 예정 파일 확인 

---

## README 생성 
README.md 파일 생성 
- 프로젝트 소개 문서

---

## Git Add 
git add README.md 
- Commit에 포함할 파일 선택 
- 실무에서는 git add . 을 더 많이 사용하는데, 이는 여러 개의 파일이 생기기 때문임 

---

## Commit
git commit -m "docs : README 파일 생성" 
- 현재 상태를 하나의 버전으로 기록 

---

## GitHUb 연결 
git remote add origin 깃허브url
- 프로젝트당 최초 1회 실행 

---

## 연결 확인 
git remote -v

---

## GitHub 업로드 
git push -u origin main

---

## Git 기본 흐름
git init > git status > git add > git commit > git push

---

## 오늘 배운 핵심 

- git init : Git 프로젝트 시작 
- git status : 현재 상태 확인 
- git add : Commit할 파일 선택 
- git commit : 버전 생성 
- git push : GitHub 업로드 

---

## 느낀점 
Git은 단순히 파일을 저장하는 프로그램이 아닌 버전을 관리하는 프로그램이다. 

작업이 끝날 때마다 의미 있는 Commit을 남기는 습관이 필요하다. 

Git 자체를 처음 사용해보는데, 아직은 익숙치 않으니 더 많이 공부해야한다. 
