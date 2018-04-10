FROM centos:7

RUN set -ex \
    \
    && yum clean all \
    && yum update -y \
    && yum -y install make automake gcc rpmbuild \
    && yum install -y epel-release rpm-build rpmdevtools \
    && yum install -y git \
    && yum install -y openssh openssh-clients \
    && yum clean all \
    && rm -rf /var/cache/yum
