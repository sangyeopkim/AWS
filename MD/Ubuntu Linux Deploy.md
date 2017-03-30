# Ubuntu Linux Deploy
> AWS EC2 + Ubuntu16.04 + Nginx + uWSGI + Django

## Setting 환경

### Ubuntu Linux
서버의 OS

### Nginx
웹 서버  
클라이언트로부터의 HTTP 요청을 받아 정적인 페이지/파일을 돌려준다.  

### Django
웹 애플리케이션  
웹 요청에 대해 동적 데이터를 돌려준다.   

### uWSGI
웹 서버(Nginx)와 웹 애플리케이션(Django)간의 연결을 중계 해 준다.  
Nginx에서 받은 요청을 Django에서 처리하기 위한 중계인 역할   

### WSGI
Web Server Gateway Interface  
python에서 웹 서버와 웹 애플리케이션간의 동작을 중계 해 주는 인터페이스  

