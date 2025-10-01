# Campus-forum-system
A campus forum system developed based on Springboot

# 앞뒤 분리 항목 :
vscode， 
node16， 
idea， 
mysql， 
navicat or mysqlworkbench， 
maven 


# 1. navicat 또는 mysqlworkbench를 열고 먼저 데이터베이스를 만든 후 데이터베이스 파일(데이터베이스 폴더)을 가져옵니다.
안)
- 주의, 시각화 링크 전에 mysql을 설치하십시오
# 2. idea를 열고 백그라운드 소스 파일(pom 파일이 있는 경우 백그라운드 파일)을 가져와 로딩 종속성을 시작합니다. 
# 3. 다운로드에 의존하는 구성 Applicaiton. yml 파일의 데이터베이스 설정
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.name=defaultDataSource
spring.datasource.url=jdbc:mysql://localhost:3306/데이터베이스 이름?
serverTimezone=UTC&useUnicode=true&characterEncoding=UTF-8
spring.datasource.username=root
spring.datasource.password=2013400236 (데이터베이스 비밀번호)
