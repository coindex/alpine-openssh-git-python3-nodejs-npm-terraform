FROM alpine:3.8

RUN apk add --update --upgrade git
RUN apk add --update --upgrade openssh-client
RUN apk add --update --upgrade python3
RUN apk add --update --upgrade postgresql
RUN apk add --update --upgrade python3-dev gcc musl-dev postgresql-dev
RUN apk add --update --upgrade nodejs
RUN apk add --update --upgrade npm
RUN apk add --update --upgrade terraform

RUN pip3 install --upgrade pip setuptools