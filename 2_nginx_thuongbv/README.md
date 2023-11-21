# How to run

- must run `docker login`  
```
docker build -t nginx_thuongbv .
docker tag nginx_thuongbv thuong99/nginx_thuongbv:v1

docker push thuong99/nginx_thuongbv:v1
docker run -d -p 8080:80 thuong99/nginx_thuongbv:v1
curl http://localhost:8080
```
