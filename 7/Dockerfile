FROM centos:7

RUN set -ex \
    \
    && yum clean all \
    && yum update -y \
    && yum install -y \
        automake \
        cmake \
        epel-release \
        gcc \
        git \
        glib2 \
        glib2-devel \
        hiredis \
        hiredis-devel \
        libcurl \
        libcurl-devel \
        libini_config \
        libini_config-devel \
        libxml2 \
        libxml2-devel \
        make \
        openssh \
        openssh-clients \
        openssl \
        openssl-devel \
        redis \
        rpmbuild \
        rpmdevtools \
    && yum clean all \
    && rm -rf /var/cache/yum