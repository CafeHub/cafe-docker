# CloudCAFE on Docker
#
# VERSION               0.1

FROM jmvrbanac/opencafe
MAINTAINER John Vrbanac <john.vrbanac@rackspace.com>
ENV CAFE_HOME  /opt/cloudcafe

ADD repo $CAFE_HOME
RUN pip install $CAFE_HOME --upgrade
