FROM node:10.15

ENV APP_ROOT /src

RUN mkdir ${APP_ROOT}
WORKDIR ${APP_ROOT}
ADD . ${APP_ROOT}

RUN npm install
RUN npm run build
RUN npm run start

ENV HOST 0.0.0.0
