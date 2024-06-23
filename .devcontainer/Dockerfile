FROM adnrv/texlive:full

# Update apt-get and install packages
RUN apt-get update && apt-get install -y --no-install-recommends \ 
    git


# Clean up
RUN apt-get autoremove -y \
    && apt-get clean -y \
    && rm -rf /var/lib/apt/lists/*
ENV DEBIAN_FRONTEND=dialog \
    LANG=C.UTF-8 \
    LC_ALL=C.UTF-8

RUN apt-get update \
&& apt-get install -y locales fonts-ipafont-gothic \
&& locale-gen ja_JP.UTF-8 \
&& update-locale LANG=ja_JP.UTF-8

ENV LANG=ja_JP.UTF-8
ENV LANGUAGE=ja_JP:ja
ENV LC_ALL=ja_JP.UTF-8