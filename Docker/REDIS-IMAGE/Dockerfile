# Use an existing docker iang as a base
FROM alpine

# Download and install a depemdancy 
RUN  apl add --update redis

# Tell the image what to do when it starts 
#as a container
CMD [ "redis-server" ]