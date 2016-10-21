FROM centos:latest
RUN yum install -y gcc make
COPY test.c /root
COPY Makefile /root
WORKDIR /root
RUN make
CMD ./test
