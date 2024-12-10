FROM node:22.11.0-alpine
WORKDIR /server
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 5000
CMD [ "npm", "run", "start" ]