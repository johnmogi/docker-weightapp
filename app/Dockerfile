FROM node:14-alpine

WORKDIR /bootcamp-app
COPY . .
RUN npm install
RUN npm run initdb
EXPOSE 2000

# CMD npm run initdb && npm run start
CMD npm run start
