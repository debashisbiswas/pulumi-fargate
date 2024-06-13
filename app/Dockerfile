FROM caddy:latest

COPY Caddyfile /etc/caddy/Caddyfile

# Expose the default Caddy HTTP port
EXPOSE 80

# Start Caddy
CMD ["caddy", "run", "--config", "/etc/caddy/Caddyfile", "--adapter", "caddyfile"]
