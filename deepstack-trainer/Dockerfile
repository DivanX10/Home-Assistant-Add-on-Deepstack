FROM divanx10/debian11-fastapi:v1

LABEL maintainer="tomer.klein@gmail.com"
ENV DEEPSTACK_HOST_ADDRESS=""
ENV HOMEASSISTANT_FOLDER_PATH_FOR_DATABASE=""
ENV HOMEASSISTANT_FOLDER_PATH_FOR_PHOTOS=""
ENV DEEPSTACK_API_KEY=""
ENV MIN_CONFIDANCE=0.70
ENV PYTHONIOENCODING=utf-8
ENV LANG=C.UTF-8

RUN apt update

RUN apt install python3-pip rsync mc nano

RUN pip3 install --upgrade pip --no-cache-dir && \
    pip3 install --upgrade setuptools --no-cache-dir

RUN mkdir -p /opt/trainer/photos/uploads
RUN mkdir -p /opt/trainer/db

COPY trainer /opt/trainer

EXPOSE 8080
WORKDIR /opt/trainer/

ENTRYPOINT ["/usr/bin/python3", "trainer.py"]
