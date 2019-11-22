FROM bde2020/hadoop-base:master

MAINTAINER Ivan Ermilov <ivan.s.ermilov@gmail.com>

COPY EchoServer.py /opt/hadoop/applications/EchoServer.py

ENV PY_FILEPATH="/opt/hadoop/applications/EchoServer.py"

EXPOSE 8080

CMD ["python", "/opt/hadoop/applications/EchoServer.py"]
