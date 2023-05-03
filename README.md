# nginx-proxypass-test

docker-compose setup to test nginx proxy_pass with whoami

## usage

1. edit nginx.conf
2. `docker-compose up`
3. Open [http://localhost:80](http://localhost:80) with the right pass in your browser
4. Check out the GET field on the whoami page to see if nginx passed the expected path
5. `docker-compose down`
6. Edit nginx.conf and restart container
