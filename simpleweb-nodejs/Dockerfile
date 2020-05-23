# Get the base image
FROM node:alpine

WORKDIR /home/app/

#When you make a workdirectory and get inside the container then bydefault this directory will open.

# Run the dependencies
# need to copy the json and js file as when you get teh base images it is inside the container's drive but 
#the package.json and node.js is not in container's drive. So you need to make sure that you have copied the
# file from file directory to container's directory.

COPY ./ ./
RUN npm install

# Command to run on container setup
CMD ["npm","start"]
