# DynamoDB Local InMemory container

AWS DynamoDB Local, with data stored in memory. This is useful to if your running integration tests, or if you don't want to hit a real DynamoDB instance during developments. Be aware that all data are removed when the container shuts down (because of the data stored in memory).

## Exposed Port :

- 8000

## Shell Access :

You can access the DynamoDB local shell by hitting the /shell URI.

> http://YOUR_DOCKER_IP:YOUR_MAPPED_PORT/shell
