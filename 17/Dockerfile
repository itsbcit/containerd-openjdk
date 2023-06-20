FROM bcit.io/alpine:3.18

LABEL maintainer="jesse@weisner.ca, chriswood.ca@gmail.com"
LABEL build_id="1687296029"

RUN apk add --no-cache \
  openjdk17

ENTRYPOINT ["/tini", "--", "/docker-entrypoint.sh"]
CMD [ "jshell" ]
