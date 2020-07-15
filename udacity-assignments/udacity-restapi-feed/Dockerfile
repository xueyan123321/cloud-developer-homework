# Set the base image
FROM node:12
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where avaiable(npm@5+)

COPY package*.json ./
RUN npm ci
# Bundle app source
COPY . .
EXPOSE 8080
CMD ["npm", "run", "prod"]