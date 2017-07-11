from debian

WORKDIR /app
ADD . /app

RUN apt-get update
RUN apt-get install -y curl
RUN apt-get install -y gnupg2
RUN curl -sL https://deb.nodesource.com/setup_8.x | bash -
RUN apt-get install -y nodejs
