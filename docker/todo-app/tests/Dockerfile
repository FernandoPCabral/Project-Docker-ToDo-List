FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/tests/
COPY package*.json ./
RUN npm install
COPY . .
CMD ["npm", "test"]
