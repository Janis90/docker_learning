FROM ubuntu:latest

# apt-get update  updates everything installed on the image
# apt-get install -y (foreces yes (must be specified)) --no-install-recommends (prevends apt-get to install any general libraries associated with vim)vim
# apt-get clean (removes temp files)
RUN apt-get update \
  && apt-get install -y --no-install-recommends vim \
  && apt-get clean
