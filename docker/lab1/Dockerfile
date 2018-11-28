FROM node

RUN mkdir -p /var/node
ADD content-express-demo-app/* /var/node/
WORKDIR /var/node
RUN npm install
CMD ./bin/www
