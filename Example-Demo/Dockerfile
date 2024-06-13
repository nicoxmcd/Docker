FROM node:14 
# Uses node.js 14 as a base image

WORKDIR /app
# Certain directory in the container to use as working directory

COPY package.json .
# We copy the package.json file to that working directory

RUN npm install
# Install needed dependencies for node.js to container

COPY . .
# Copies the rest of the code into the working directory of the container

EXPOSE 3000
# Exposes the port of our application to the outside world essentially so we can reach it outisde of the container

CMD ["node", "app.mjs"]
# Execute app.mjs with the node command