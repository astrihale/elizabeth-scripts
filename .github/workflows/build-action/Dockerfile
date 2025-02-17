FROM node:alpine
WORKDIR /app
COPY package.json package-lock.json tsconfig.json /app/
RUN npm install
COPY src /app/src
RUN npm run build