# base images alpine light flavor of linux
FROM alpine

# get redis in alpine
# commands to extra programs
# apk is package manager in alpine
RUN apk add --update redis

# Start redis server
# run the process
CMD ["redis-server"]

# to connect to this use exec and run redis-cli to connect to this redis server