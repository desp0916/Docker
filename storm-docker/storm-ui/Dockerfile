#FROM wurstmeister/storm:0.9.4
FROM desp0916/storm:0.10.0-beta1

MAINTAINER Wurstmeister
RUN /usr/bin/config-supervisord.sh ui

EXPOSE 8080
CMD /usr/bin/start-supervisor.sh





