FROM ubuntu
MAINTAINER mathashallex32@gmail.com
RUN sudo apt-get update && \
#Install curl
sudo apt-get -y install curl && \
#setup and install node js
curl -sL https://deb.nodesource.com/setup || sudo bash - && \
sudo apt-get install -y nodejs && \
sudo apt-get install -y git && \
cd home && \
git clone https://github.com/allex32/speech-recognition
