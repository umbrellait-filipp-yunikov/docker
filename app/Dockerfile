FROM node:12-alpine as builder
WORKDIR /bindmount
COPY . ./
RUN npm install --no-progress --ignore-optional
CMD npm start
EXPOSE 8080