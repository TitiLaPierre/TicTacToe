FROM node:22.22.0-trixie-slim
WORKDIR /app

COPY package*.json .
RUN npm install
COPY . .

CMD ["npm", "start"]