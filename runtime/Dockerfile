FROM alpine:3.9 as builder

# install hugo
RUN apk add --no-cache bash net-tools && \
    wget https://github.com/gohugoio/hugo/releases/download/v0.54.0/hugo_0.54.0_Linux-64bit.tar.gz && \
    tar -zxvf hugo_0.54.0_Linux-64bit.tar.gz -C /usr/local/bin/ && \
    rm -rf hugo_0.54.0_Linux-64bit.tar.gz
