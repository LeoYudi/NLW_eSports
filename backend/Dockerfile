FROM node:16-alpine as deps
WORKDIR /
COPY . .
RUN yarn install && yarn build
CMD ["yarn", "start"]

EXPOSE 3000