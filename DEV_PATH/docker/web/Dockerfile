FROM python:3.8

COPY ./app /srv/www/app
WORKDIR /srv/www/app

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# RUN apk update \
#     && apk add postgresql-dev gcc python3-dev musl-dev

RUN pip install --upgrade pip
RUN pip install -r requirements.txt