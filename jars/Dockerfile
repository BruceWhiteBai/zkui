FROM java:8

MAINTAINER jim <baizhoujun@sunlands.com>

WORKDIR /var/app

ADD zkui-*.jar /var/app/zkui.jar
ADD config.cfg /var/app/config.cfg

ENTRYPOINT [ "java", "-jar", "/var/app/zkui.jar" ]

EXPOSE 9090