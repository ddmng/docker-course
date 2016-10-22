FROM node:latest

RUN npm install express --save
COPY test.js /root
COPY Makefile /root
WORKDIR /root
EXPOSE 3000

CMD node test.js
