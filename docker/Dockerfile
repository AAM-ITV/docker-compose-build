FROM maven:3.8.6-openjdk-11-slim
RUN apt update 
RUN apt install git -y
RUN git clone https://github.com/AAM-ITV/exam /tmp/boxfuse/exam
WORKDIR /tmp/boxfuse/exam
RUN mvn package
CMD ["tail", "-f", "/dev/null"]
