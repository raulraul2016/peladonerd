FROM python:3.10.5-buster
RUN pip install redis
COPY ./worker.py /worker.py
COPY ./rediswq.py /rediswq.py

CMD  python worker.py
