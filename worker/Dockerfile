FROM node:22.11.0-alpine
WORKDIR /worker
COPY ./package*.json ./
RUN npm install
COPY . .
CMD [ "npm", "run", "start" ]