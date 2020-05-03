#FROM phusion/baseimage:0.11
FROM samip537/phusion-baseimage-test:upgrade-to-ubuntu-focal-amd64
MAINTAINER Phusion <info@phusion.nl>

ADD . /pd_build
RUN /pd_build/install.sh
CMD ["/sbin/my_init"]
EXPOSE 80 443
