FROM docker:20.10.16
RUN apk add --no-cache curl jq python3 py3-pip
RUN pip install awscli
RUN apk add --update coreutils && rm -rf /var/cache/apk/*