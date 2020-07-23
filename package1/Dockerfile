FROM node:12.16.1-alpine

RUN npm config set unsafe-perm true


RUN mkdir -p /opt/app
COPY . /opt/app
WORKDIR /opt/app

CMD ["yarn"]