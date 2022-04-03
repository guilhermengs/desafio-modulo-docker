FROM node:15                

WORKDIR /usr/src/app         

COPY Dockerfile index.js package.json package-lock.json ./

RUN npm install

RUN mkdir node_modules/.cache && chmod -R 777 node_modules/.cache

EXPOSE 3000

ENTRYPOINT ["node", "index.js"]
