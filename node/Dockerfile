FROM node:carbon

ARG PORT

RUN npm install -g yarn @feathersjs/cli feathers-cli

# Create app directory
RUN mkdir -p /usr/src/app && mkdir /usr/src/app/api
WORKDIR /usr/src/app/api

EXPOSE $PORT
CMD [ "npm", "start" ]
