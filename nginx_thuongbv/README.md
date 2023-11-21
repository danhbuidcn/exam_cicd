# How to run

- must run `docker login`  
```
cd nginx_thuongbv
docker build -t nginx_thuongbv .
docker tag nginx_thuongbv thuong99/to_examine:v1

docker push thuong99/to_examine:v1
docker run -d -p 8080:8080 thuong99/to_examine:v1
curl http://localhost:8080
```
