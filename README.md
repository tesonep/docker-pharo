# Docker-Pharo

Docker image for pharo [basmalltalk/docker-pharo](https://hub.docker.com/r/basmalltalk/docker-pharo/)

The Pharo VM is in _/opt/pharo_, under user `pharo`

The user UID and group GID can be customized on build, default to 7431.

## Useful stuff:

- [How to](docs/rtprio.md) deal with `pthread_setschedparam failed: Operation not permitted`
- [Examples](docs/Examples.md) of Dockerfiles and docker-compose.yml