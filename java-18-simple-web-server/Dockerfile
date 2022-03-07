FROM docker.io/library/openjdk:18-jdk-slim
ENV TXT_TST="testing 1 2"
USER 1001
EXPOSE 8000
WORKDIR ~/app
CMD ["/bin/bash", "-c", "echo \"<html><body>$TXT_TST</body></html>\" > index.html && jwebserver -b 0.0.0.0"]
