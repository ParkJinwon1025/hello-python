# hello-python

# VSCode 파이썬 가상환경 빌드 

# 📑 목차

1. [**프로젝트를 새롭게 생성**](#1-프로젝트를-새롭게-생성)
2. [**프로젝트 Git Clone**](#2-프로젝트-git-clone)

## 1. 프로젝트를 새롭게 생성

1. Ctrl + Shift + p 입력
2. `>Python : Create Environment` 클릭
3. `Venv` 클릭 후 계속 엔터 입력
4. 현재 폴더에 `.venv` 폴더 생성 확인
5. `hello.py` 생성 ( 이름은 상관 없음. )
6. 아무 코드 입력 후 우측 상단의 화살표 버튼 클릭
7. 결과 확인
8. 라이브러리 사용할 경우 해당 명령어 입력
```cmd
pip freeze > requirement.txt
```

## 2. 프로젝트 Git Clone

1. 파이썬 3.13.9 설치

 >**Requirement python 3.9.x** 이상

2. Git clone
```bash
git clone https://github.com/ParkJinwon1025/hello-python.git
```
3. 디렉터리 이동
```bash
cd hello-python
```

4. 파이썬 가상환경 생성
```bash
python -m venv .venv
```
5. 권한 변경( Window PowerShell 실행 후 명령어 실행 )
```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

5. 가상환경으로 전환( 3번에서 이동한 디렉토리에서 실행 )
```bash
.\.venv\Scripts\activate  
```

6. 패키지 설치
```bash
pip install -r requirements.txt
```

7. hello.py 실행
```bash
python .\hello.py
```

8. 가상환경 비활성화
```bash
deactivate
```