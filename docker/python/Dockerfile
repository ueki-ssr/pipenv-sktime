FROM python:3.8

WORKDIR /app

RUN pip install --upgrade pip

RUN pip install pipenv

RUN pipenv install -d

# ENTRYPOINT ["/bin/sh", "-c", "while :; do sleep 10; done"]
