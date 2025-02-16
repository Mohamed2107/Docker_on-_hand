FROM node:14

WORKDIR /app

COPY server.js .
COPY index.html .
COPY images ./images
COPY package.json .

RUN npm install 


ENV APP_NAME="MyApp"

EXPOSE 3000

CMD ["node", "server.js"]
