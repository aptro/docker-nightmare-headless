FROM node:4.4.6

RUN apt-get update &&\
    apt-get install -y libgtk2.0-0 libgconf-2-4 \
    libasound2 libxtst6 libxss1 libnss3 xvfb

RUN Xvfb -ac -screen scrn 1280x2000x24 :9.0 &&\
    export DISPLAY=:9.0