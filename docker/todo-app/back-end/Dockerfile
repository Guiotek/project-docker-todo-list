FROM node:14 

EXPOSE 3001

WORKDIR /todo-app/back-end

ADD node_modules.tar.gz .

COPY . .

CMD ["npm", "start"]
