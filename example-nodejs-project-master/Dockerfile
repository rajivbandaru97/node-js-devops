FROM node:latest

WORKDIR /example-nodejs-project-master

COPY Rakefile ./

RUN npm install

COPY . .

EXPOSE 3000
CMD [ "node", "server.js"]
