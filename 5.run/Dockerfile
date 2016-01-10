FROM 4.git

EXPOSE 88

#RUN echo 192.168.0.10 dbHost >> /etc/hosts

RUN rm -f /claude-0.001/RUNNING_PID

#CMD ["claude-0.001/bin/claude", "-Dhttp.port=88"]

ADD ./startup.sh /startup.sh

CMD ["/bin/bash", "startup.sh"]