FROM python:3.9

WORKDIR /app

ADD ./app /app

RUN pip install -r requirements.txt

EXPOSE 8080

ENTRYPOINT python /app/app.py runserver 0.0.0.0:8080
