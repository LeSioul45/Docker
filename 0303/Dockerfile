FROM node:latest

ARG NAME
ENV NAME=${NAME}

WORKDIR /app

ADD ./index.js /app/index.js

RUN echo ${NAME}

CMD NAME=${NAME} node index.js
