FROM node:12-alpine

WORKDIR /root/server

COPY package.json package.json
COPY package-lock.json package-lock.json
RUN npm install

CMD ["time", "npm", "start" ]
