# Use existing base image
FROM alpine

# Download and run all the dependencies

RUN apk add --update gcc
RUN apk add --update redis

#Tell image what to do when it starts as a container
CMD ["redis-server"]


