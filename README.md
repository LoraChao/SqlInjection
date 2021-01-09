# SqlInjection
These codes are working on DVWA "sqlInjection and blind sqlInjection" for all security level.
DVWA is using:
database: mysql 
server: apache2
SqlInjection has echo page, so we just need to build injection mysql lines.
Blind SQLInjection (without echo page): we have to use time() function and observe page response time, for makesure if the injection lines is true
