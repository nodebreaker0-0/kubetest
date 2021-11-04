2-2) Docker Hub Site
https://hub.docker.com/

2-3) Docker Container Run
docker build -t wptjs123/hello .
-t : 레파지토리/이미지명:버전

docker images
docker run -d -p 8100:8000 wptjs123/hello
-d : 백그라운드 모드
-p : 포트변경

docker ps
docker exec -it c403442e8a59 /bin/bash

2-4) Docker Image Push
docker login
docker push wptjs123/hello


