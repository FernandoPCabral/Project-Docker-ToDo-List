FROM node:14-alpine
WORKDIR /docker/todo-app/back-end/
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3001
ENTRYPOINT ["npm", "start"]