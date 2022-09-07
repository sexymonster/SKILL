# 프로젝트 전 가상환경 설정
1. 콘다에서 가상환경 생성
2. 로컬에 딕셔너리 생성
3. vscode에서 로컬에 생성한 폴더를 열고, 버전 환경을 생성한 가상환경으로 설정
4. 필요한 라이브러리 설치 (ex. pip install flask)

# 플라스크 개발 준비!
app.py 파일을 생성
터미널에 >flask run 을 입력하면 디폴트로 app.py가 실행됨
app.py 가 아니라 pybo.py 일 경우 아래 코드를 실행 시키면 디폴트가 pybo.py로 됨
set FLASK_APP=pybo
디버깅이 가능하도록 하기 위해서
set FLASK_DEBUG=true
도 실행

매번 입력하기 힘들기 때문에 cmd파일 생성
'''python
@echo off
set FLASK_APP=pybo
set FLASK_DEBUG=true
'''

