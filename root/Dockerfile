FROM node:10.16.0
WORKDIR /usr/local/docker/app
COPY ./ /usr/local/docker/app
RUN npm ci
ENTRYPOINT [ "./bin/start" ]