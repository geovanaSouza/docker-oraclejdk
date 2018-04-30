FROM centos:7
MAINTAINER Geovana Possenti <geovana.possenti@gmail.com>

RUN yum update -y
RUN yum install -y wget && wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u11-b12/jdk-8u171-linux-x64.rpm
RUN rpm -ivh jdk-8u171-linux-x64.rpm && rm jdk-8u171-linux-x64.rpm
