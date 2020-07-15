# set the base image
FROM node:12

# create the app directory
WORKDIR /usr/src/app
# Install app dependencies
# A wildcard is used to ensure both package.json and package-lock.json are copied
COPY package*.json ./
RUN npm ci
#bundle the app src
COPY . .
EXPOSE 8080
CMD ["npm", "run", "prod"]