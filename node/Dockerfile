# base image
FROM node:16-alpine

WORKDIR /app

# Copy all the files in this host dir(relative to Dockerfile) to inside the conatiner
# look into the file using sh
# not advised to keep files inthe root directory 
# hence used workdir to copy stuff there
COPY ./package.json .

# install node and run npm install
RUN npm install

COPY . .

# run server
CMD [ "npm", "start" ]

