FROM node:23-alpine3.20

WORKDIR /frontend

COPY . . 

RUN rm -rf /node_modules || true

RUN npm install

RUN npm install -g @angular/cli



CMD ng serve --host 0.0.0.0 --disable-host-check


