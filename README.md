# flask-pybo
점프 투 플라스크 clone 레포지토리입니다.
https://wikidocs.net/book/4542


<hr>

# 정리

1장 플라스크 개발 준비
## 플라스크 애플리케이션을 생성하는 코드 : Flask(__name__)
 - __name__이라는 변수에는 모듈명이 담김
 - 즉, 이 파일이 실행되면 pybo.py라는 모듈이 실행됨으로 __name__변수에는 pybo라는 문자열이 담김

## 플라스크는 FLASK_APP 환경변수가 지정되지 않은 경우 자동으로 app.py파일을 기본 애플리케이션으로 인식
 - FLASK_APP 환경변수를 별도로 지정해야한다. 
 - export FLASK_APP=pybo
 
## 디버그 모드 활성화
 - 디버그 모드는 오류가 발생하면 디버깅 결과 메시지를 웹 브라우저에 출력해 준다.
 - 또한 서버 실행중에 프로그램을 변경하면 서버가 자동으로 다시 시작하여 변경된 내용을 적용해 준다.
 - export FLASK_DEBUG=true
