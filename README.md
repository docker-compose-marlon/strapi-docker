# Create a Strapi Docker
```
git clone https://github.com/docker-compose-marlon/strapi-docker
cd strapi-docker
docker-compose up -d
```

# docker swarm
```
docker swarm init
docker-compose build
docker stack deploy strapi -c docker-compose.yml
docker stack ls
```
