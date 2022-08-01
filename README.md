# sample-docker-compose script 

## Commands
```
docker build -t testnginx:gama3 -f Dockerfile .
docker run -p 8084:80 testnginx:gama3
docker-compose -d up
docker-compose down
```
