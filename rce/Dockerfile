#comment: This Dockerfile is used to create a simple container that pings google.com
#comment: It uses Alpine Linux as the base image and installs Python3
#comment: The container will ping google.com 5 times when run
#comment: The ENTRYPOINT is set to ping with a count of 5
#comment: The CMD specifies the target to ping  
#comment: This is example of RN vs CMD vs ENTRYPOINT

FROM alpine

RUN apk add python3

CMD [ "google.com" ]

ENTRYPOINT [ "ping", "-c", "5" ]