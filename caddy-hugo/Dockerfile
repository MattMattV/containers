FROM abiosoft/caddy:0.11.0

ENV HUGO_VERSION=0.42.1

RUN apk --no-cache add curl 

RUN curl -L https://github.com/gohugoio/hugo/releases/download/v${HUGO_VERSION}/hugo_${HUGO_VERSION}_Linux-64bit.tar.gz --output /tmp/hugo.tar.gz && \
    tar -xvzf /tmp/hugo.tar.gz -C /tmp && \
    mv /tmp/hugo /bin && \
    chmod +x /bin/hugo