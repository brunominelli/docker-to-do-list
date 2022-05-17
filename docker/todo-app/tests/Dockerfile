FROM node:14-alpine
WORKDIR /docker/todo-app/front-end/
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY . .
ENTRYPOINT ["npm", "test"]
