FROM node:20
WORKDIR /app
COPY package.json .
COPY *.js .
RUN npm install
ENV REDIS_HOST="redis" \
    CATALOUGE_HOST="catalouge" \
    CATALOUGE_PORT="8080"
CMD ["node", "server.js"]
