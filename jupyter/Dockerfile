FROM python:latest
RUN mkdir /app
COPY . /app
WORKDIR /app

RUN mkdir /data
RUN apt update
RUN apt upgrade -y
RUN apt-get install software-properties-common -y
RUN python3 -m pip install --upgrade pip
RUN apt-get install nodejs -y 
RUN apt-get install npm -y
RUN pip install jupyterlab
RUN pip install pandas
#RUN pip install json
RUN pip install requests

