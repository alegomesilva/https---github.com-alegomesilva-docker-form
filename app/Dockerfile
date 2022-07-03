FROM node:18-alpine3.15
LABEL maintainer "Alessandro <ale.gomesilva79@gmail.com>"
COPY . /app
WORKDIR /app
RUN npm install
ENTRYPOINT node index.js
EXPOSE 8080
CMD ["npm", "run", "start"]