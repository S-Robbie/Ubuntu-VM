FROM alpine:latest
COPY stack.yaml /stack.yml
ADD stack.yaml /rob.yml
VOLUME mydbvol /data
ENV key1=val1
ENTRYPOINT /bin/sh
CMD ['echo', 'hello']