FROM node
#  Build container from node image found on Docker Hub

WORKDIR /app
# Set working directory to the app folder

COPY . /app
# All files in this folder should be copied to the image folder app

RUN npm install

EXPOSE 80
# When container is created, expose the port to our local machine

CMD ["node", "server.js"]
# Runs only when a container based on the image template is created 

