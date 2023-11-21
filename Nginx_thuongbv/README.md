# How to run
docker build -t my-nginx-image .
docker tag my-nginx-image your-repository/my-nginx-image:latest

docker push your-repository/my-nginx-image:latest
docker run -d -p 8080:8080 your-repository/my-nginx-image:latest
curl http://localhost:8080
