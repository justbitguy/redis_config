FROM redis:latest

COPY redis.conf /usr/local/etc/redis/redis.conf

EXPOSE 6379 

RUN chmod 644 /usr/local/etc/redis/redis.conf

CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]

