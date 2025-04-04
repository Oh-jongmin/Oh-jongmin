# Docker 명령어

## Docker Hub에서 이미지 다운로드
docker pull [이미지명]

## 내 PC에 저장된 이미지 목록 확인
docker images/docker image ls

## 이미지 삭제
docker rmi [이미지명/ID]

## 컨테이너 실행
docker run [옵션] 이미지명

## 실행 중인 컨테이너 목록
docker ps

## 중지된 것 포함한 모든 컨테이너
docker ps -a

## 컨테이너 중지
docker stop [컨테이너ID/컨테이너명]

## 컨테이너 삭제
docker rm [컨테이너ID/컨테이너명]

## 현재 디렉토리의 Dockerfile로 이미지 빌드
docker build -t [이미지명] .

## 이미지 이름 변경/버전 태그 추가
docker tag [이미지명] [이미지명:태그]

## 상세 정보 확인
docker inspect [컨테이너ID/컨테이너명]

## 실행 중인 컨테이너의 내부에서 실행
docker exec -it [컨테이너] bash

## 로그 확인
docker logs [컨테이너]

## 중지된 컨테이너 전부 삭제
docker container prune

## 사용되지 않는 이미지 삭제
docker image prune

## 모든 불필요한 이미지, 컨테이너, 네트워크 삭제
docker system prune -a