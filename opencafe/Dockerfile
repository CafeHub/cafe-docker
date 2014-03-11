# OpenCAFE on Docker
#
# VERSION               0.1

FROM jmvrbanac/ubuntu-pyenv:saucy
MAINTAINER John Vrbanac <john.vrbanac@rackspace.com>
ENV CAFE_HOME  /opt/opencafe

ADD repo $CAFE_HOME
RUN pip install $CAFE_HOME --upgrade
