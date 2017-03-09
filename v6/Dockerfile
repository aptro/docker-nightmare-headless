FROM node:6

RUN apt-get update && \
    apt-get install -y \
        postgresql-client-9.4 \
        xvfb \
        x11-xkb-utils \
        xfonts-100dpi \
        xfonts-75dpi \ 
        xfonts-scalable \
        xfonts-cyrillic \
        x11-apps \
        clang \
        libdbus-1-dev \
        libgtk2.0-dev \
        libnotify-dev \
        libgnome-keyring-dev \
        libgconf2-dev \
        libasound2-dev \
        libcap-dev \
        libcups2-dev \
        libxtst-dev \
        libxss1 \
        libnss3-dev \
        gcc-multilib \
        g++-multilib \
        xauth \
        git \
        sudo \
        --no-install-recommends \
    && apt-get autoclean \
    && apt-get clean \
    && rm -rf /var/lib/api/lists/*