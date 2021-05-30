FROM node:12-alpine

COPY . /app

WORKDIR /app

RUN yarn install

EXPOSE 3000

ENTRYPOINT ["yarn", "run", "dev"]
