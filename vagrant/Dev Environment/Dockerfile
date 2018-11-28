FROM node:alpine
COPY code /code
WORKDIR /code
RUN npm install --production
EXPOSE 3000
CMD ["node", "app.js"]
