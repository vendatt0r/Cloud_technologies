FROM ubuntu:jammy-20231004
RUN mkdir test
COPY service1.py /test
WORKDIR /test
RUN apt-get update && apt-get install -y python3-pip && pip install numpy
EXPOSE 8081
# CMD [ "python3", "service1.py"]