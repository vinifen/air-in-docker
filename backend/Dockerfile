#backend
FROM node:23-alpine3.20

WORKDIR /backend

COPY . .

RUN rm -rf /frontend/node_modules || true

RUN npm install

CMD npm run dev


