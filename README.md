# Description:

This adds additional resources on top of 

### Dockerfile:
```dockerfile
FROM rkhtech/awscli:latest

MAINTAINER Randy Hommel

RUN apk add php7-cli zip
```

#### References:
* [https://github.com/rkhtech/awscli](https://github.com/rkhtech/awscli)
* [https://hub.docker.com/r/rkhtech/awscli](https://hub.docker.com/r/rkhtech/awscli)
