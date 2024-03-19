FROM python:3.12-slim-bullseye

ENV PYTHONUNBUFFERED=1

RUN apt update
RUN apt install -y git

RUN pip install -U pip && \
    pip install twine build

CMD ["/bin/bash"]