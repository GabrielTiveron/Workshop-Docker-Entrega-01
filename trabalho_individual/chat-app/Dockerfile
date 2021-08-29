FROM node:15.13-alpine

WORKDIR /src

ENV PATH="./node_modules/.bin:$PATH"

COPY package*.json ./

COPY . .

RUN yarn

EXPOSE 7001

CMD ["yarn", "watch"]
