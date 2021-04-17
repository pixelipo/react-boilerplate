FROM node:current-alpine

WORKDIR /app

COPY package.json yarn.lock /app

RUN yarn install

COPY . /app

# Start app
CMD ["yarn", "run", "start"]
