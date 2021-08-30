FROM node:15.13-alpine

WORKDIR /src

COPY package*.json ./

COPY . . 

RUN yarn

EXPOSE 7100

CMD ["yarn", "watch"]
