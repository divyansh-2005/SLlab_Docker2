free -h  # memory ram assigned

lscpu # cpus 

df -h # disk

cat /etc/os-release

docker version

# hub.docker.com

# nginx   - web server

docker pull nginx

docker images
docker image ls
docker ps -a
docker run --name nginx -p 80:80 nginx
docker ps -a
docker container ls -a
docker start nginx 
docker stop nginx
docker rm nginx
docker container ls -a
docker run --name nginx -p 8000:80 -d nginx
## daemon mode the option -d
curl http://localhost:8000
docker logs -f nginx
## use control + c to stop
## -f means follow
docker rm -f nginx
docker run -it --name nginx -p 8000:80 -d nginx
docker ps
docker exec -it nginx bash
cat /etc/os-release
curl http://localhost
docs.docker.com

