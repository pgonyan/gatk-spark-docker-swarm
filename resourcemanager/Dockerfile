FROM esitull/stack-hadoop-docker:hadoop

ADD run.sh /run.sh
RUN chmod a+x /run.sh

EXPOSE 8030
EXPOSE 8031
EXPOSE 8032
EXPOSE 8088

CMD ["/run.sh"]
