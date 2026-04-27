FROM node:24-alpine
WORKDIR /app

COPY react-board/package*.json ./
RUN npm install 

COPY react-board/ ./
RUN npm run build
