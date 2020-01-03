#base image

FROM node:8-alpine

#coping package.json
WORKDIR /app
COPY ./package.json ./

## INSTALL NPM

RUN npm install

COPY ./ ./

##command
CMD ["npm", "run", "start"]

