FROM node:current-alpine

WORKDIR /app

COPY package.json yarn.lock /app

RUN yarn install

COPY . /app

# EXPOSE 3000

CMD ["yarn", "run", "start"]
