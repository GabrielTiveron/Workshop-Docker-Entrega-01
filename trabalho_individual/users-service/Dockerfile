FROM node:15.13-alpine

WORKDIR /src

COPY . .

RUN yarn

EXPOSE 7101

CMD ["sh", "-c", "yarn db:migrate;yarn watch"]
