# max-docker-http-https

```
docker build -t nginx-ssl:latest .
docker run -p 80:80 -p 443:443 --name nginx-ssl -tid nginx-ssl
```

then navigate to http://localhost/sample.html ->  https://localhost/sample.html
