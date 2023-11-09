FROM ubuntu
COPY . /test
WORKDIR /test
RUN apt-get update
RUN apt-get install -y python3-pip
RUN apt-get install -y nodejs
RUN apt-get install snap -y
RUN apt-get install curl -y
RUN pip install numpy
RUN pip install pandas
EXPOSE 8081
RUN python3 service1.py
# CMD [ "python3", "service1.py"]
