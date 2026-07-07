FROM quay.io/centos/centos:stream9

RUN ["/usr/sbin/useradd", "user01"]
RUN ["whoami"]
RUN ["id"]

USER user01
RUN ["whoami"]
RUN ["id"]
