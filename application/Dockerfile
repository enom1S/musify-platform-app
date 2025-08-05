FROM node:latest

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 8080
CMD ["node", "backend_structure.js"]
