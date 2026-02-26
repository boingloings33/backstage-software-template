FROM python:3.6.9-slim-stretch

COPY ./requirements.txt .

RUN pip install -r ./requirements.txt

COPY src /src

CMD python /src/app.py
