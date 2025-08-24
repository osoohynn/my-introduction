docker build --platform linux/amd64 -t my-introduction .

docker tag my-introduction osoohynn3/my-introduction:latest

docker push osoohynn3/my-introduction:latest

-- 리눅스 환경에서
docker pull osoohynn3/my-introduction:latest

docker run -d -p 8080:8000 --name my-intro-app osoohynn3/my-introduction:latest