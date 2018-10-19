FROM centos:7
MAINTAINER Geovana Possenti <geovana.possenti@gmail.com>

ENV LANG C.UTF-8

RUN yum update -y
RUN yum install -y wget which && wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u191-b12/2787e4a523244c269598db4e85c51e0c/jdk-8u191-linux-x64.rpm
RUN rpm -ivh jdk-8u191-linux-x64.rpm && rm jdk-8u191-linux-x64.rpm

RUN ln -svT "/usr/java/jdk1.8.0_191-amd64" /docker-java-home
ENV JAVA_HOME /docker-java-home

