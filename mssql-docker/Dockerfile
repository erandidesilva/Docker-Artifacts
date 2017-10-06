FROM microsoft/mssql-server-linux:2017-GA

ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8

ADD entrypoint.sh /
ADD init.sh / 

RUN chmod +x /entrypoint.sh
RUN chmod +x /init.sh

EXPOSE 1433

ENTRYPOINT ["/entrypoint.sh"]


