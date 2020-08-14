# HAProxy-w-nginx use Docker Compose
I did a demo using haproxy load balancing on nginx with Docker Compose


RUN:

docker-compose up websrv

docker-compose scale websrv=5

docker-compose up loadbalance

