FROM python:3.7-alpine

WORKDIR /bots
COPY ./bots ./bots
COPY requirements.txt .
RUN pip3 install -r ./requirements.txt

WORKDIR /bots
CMD ["python3", "./bots/favretweet.py"]