# docker-cra

Deploy React app in Docker Container

## docker build (도커 이미지 생성)

`docker build --tag <name>:<version> .`

## docker run (컨테이너 생성 후 도커 이미지 실행)

`docker run --name <container-name> -p 3000:3000 <image-name>:<version>`

## docker ps -a (모든 컨테이너 목록 출력)

`docker ps -a`

## docker stop (컨테이너 정지)

`docker stop <container-name>`

## docker stop (컨테이너 실행)

`docker start <container-name>`

## docker rm (컨테이너 삭제)

`docker rm <container-name>`

## docker image ls (모든 이미지 목록 출력)

`ocker image ls`

## docker rmi (이미지 삭제)

`docker rmi <image-name>:<version>`
