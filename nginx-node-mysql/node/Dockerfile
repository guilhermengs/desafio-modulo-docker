FROM node:15                

WORKDIR /usr/src/app         

COPY Dockerfile index.js package.json  package-lock.json .

EXPOSE 3000

ENTRYPOINT ["node", "index.js"]
