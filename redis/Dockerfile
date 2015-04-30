#
# Redis Dockerfile
#
# https://github.com/dockerfile/redis
#

FROM redis

# Define mountable directories.
VOLUME ["/data"]

# Define working directory.
WORKDIR /data

# Define default command.
ENTRYPOINT ["redis-server"]

# Expose ports locally on VM
EXPOSE 6379
