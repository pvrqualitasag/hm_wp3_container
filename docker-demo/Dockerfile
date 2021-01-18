FROM ubuntu

RUN apt-get -y update
RUN apt-get install -y python

WORKDIR /app

ADD . /app 

CMD ["python", "/app/my_script.py"]
