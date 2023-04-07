FROM node:12.18.3

WORKDIR /app

COPY package.json .
# COPY package-lock.json .

RUN npm install

COPY . .

CMD [ "node", "index.js" ]

# run lệnh: docker build -t 080196/hello-cm .