FROM node:lts-alpine
WORKDIR '/app'
COPY ./package.json ./
RUN apk add --no-cache make gcc g++ python2
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
