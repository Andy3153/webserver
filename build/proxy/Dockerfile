#FROM caddy:builder-alpine AS builder
#RUN xcaddy build \
#    --with github.com/mholt/caddy-dynamicdns\
#    --with github.com/caddy-dns/duckdns

FROM caddy:latest
#COPY --from=builder /usr/bin/caddy /usr/bin/caddy
COPY Caddyfile /etc/caddy/Caddyfile
