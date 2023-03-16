ARG BASE_IMAGE_TAG=latest
FROM ubuntu:${BASE_IMAGE_TAG}

RUN apt-get update && apt-get install -y ffmpeg

ENTRYPOINT ["ffmpeg"]