FROM node:12.18.4-alpine3.9
WORKDIR json-server
COPY db.json .

RUN npm install -g json-server@^0.16.1

EXPOSE 3001

CMD json-server --watch db.json --host 0.0.0.0 --port 3001
