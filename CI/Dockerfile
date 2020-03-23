
FROM docker:stable

RUN apk update \
    && apk upgrade \
    && apk add python python-dev py-pip build-base libffi-dev openssl-dev libgcc \
    && pip install docker-compose==1.25.4 \
    && rm /var/cache/apk/*
