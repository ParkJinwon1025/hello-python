# VSCode 파이썬 가상환경 빌드

1. 파이썬 3.13.9 설치

 >**Requirement python 3.9.x** 이상

2. Git clone
```
git clone https://github.com/ubisam-research/com.ubisam.persons.parkjinwon2.git
```
3. 디렉터리 이동
```
cd com.ubisam.persons.parkjinwon2
```

4. 파이썬 가상환경 생성
```
python -m venv .venv
```
5. 권한 변경( Window PowerShell 실행 후 명령어 실행 )
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

5. 가상환경으로 전환( 3번에서 이동한 디렉토리에서 실행 )
```
.\.venv\Scripts\activate  
```

6. 패키지 설치
```
pip install -r requirements.txt
```

7. hello.py 실행
```
python .\hello.py
```