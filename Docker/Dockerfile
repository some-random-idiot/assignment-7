FROM node:12.18.1-alpine

WORKDIR /usr/src/app
ENV PORT 32100
EXPOSE 32100

COPY package*.json ./
COPY SampleVideo_1280x720_1mb.mp4 ./
COPY index.js ./

RUN npm install
CMD npm start