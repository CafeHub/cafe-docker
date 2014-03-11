# CloudRoast on Docker
#
# VERSION               0.1

FROM jmvrbanac/cloudcafe
MAINTAINER John Vrbanac <john.vrbanac@rackspace.com>
ENV CAFE_HOME  /opt/cloudroast

ADD repo $CAFE_HOME
RUN pip install $CAFE_HOME --upgrade
