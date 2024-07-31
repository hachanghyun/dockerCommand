# dockerCommand

## docker 컨테이너 실행중인 목록 조회
    docker ps

## docker에서 컨테이너 실행 or pull받아와서 실행
    docker run nginx

## docker 컨테이너 실행중 & 이전에 멈춘 컨테이너 목록 조회
    docker ps -a

## docker 컨테이너 stop
    docker stop silly_samment(names or container id)

## docker contaioner remove
    docker rm silly_sammet

## docker image list
    docker images

## docker remove images
    docker rmi nginx

## download an image
    docker pull nginx

## docker append a command 
    dockcer rum ubuntu sleep 5

## execute a command 
    docker exec distracted_mcclintock cat /etc/host

## attach and detach
    docker run kodekloud/simple-webapp

## background docker container execute
    docker run -d kodekloud/simple-webapp

## 도커 컨테이너를 가져오고 그 컨테이너 bash로 이동
    docker run -it centos bash

## 도커 컨테이너 20초동안만 실행하고 백그라운드(-d)로 실행
    docker run -d centos sleep 20

## 도커 Run -tag
    docker run redis
    docker run redis:4.0




