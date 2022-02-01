# rest-webservice-springboot

docker build -t rest-webservice -f Dockerfile  .

docker tag rest-webservice rahulwagh17/rest-webservice:rest-webservice

docker run -p 8080:9090 -t rahulwagh17/rest-webservice:rest-webservice


docker run -p 9090:9090 -t rest-webservice -f Dockerfile  .