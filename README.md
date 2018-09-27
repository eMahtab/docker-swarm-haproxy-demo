## Docker Swarm HAProxy Demo



To run this locally, run:

```
docker swarm init
git clone https://github.com/eMahtab/docker-swarm-haproxy-demo.git
cd docker-swarm-haproxy-demo
docker build -t haproxy-demo:1.0 .
docker stack deploy -c ./docker-compose.yml vibrant
```

To tear down the stack:
```
docker stack rm vibrant
```
