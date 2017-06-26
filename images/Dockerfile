FROM openjdk:8u102-jre
MAINTAINER leapar <leapar@gmail.com>

ADD config.conf /usr/local/vcenter/config.conf
ADD VcenterCollector.jar /usr/local/vcenter/VcenterCollector.jar
WORKDIR /usr/local/vcenter/
CMD ["java","-jar","VcenterCollector.jar","start","config.conf"]

#docker run  -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_ROOT_HOST=% -p 3306:3306 -d mysql/mysql-server:5.7
#java -jar VcenterCollector-0.0.1-SNAPSHOT.jar start config