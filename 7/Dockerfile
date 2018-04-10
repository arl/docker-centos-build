FROM centos:7

RUN set -ex \
    \
    && yum clean all \
    && yum update -y \
    && yum -y install make automake gcc rpmbuild \
    && yum clean all \
    && rm -rf /var/cache/yum
