# nginx-proxypass-test

docker-compose setup to test nginx proxy_pass with whoami

## usage

1. edit nginx.conf
2. `docker-compose up`
3. use curl to check URI `curl -i localhost:80/app1`
   1. be cautious when using browser instead of curl, because of page caching
4. Check out the GET field on the whoami page to see if nginx passed the expected path
5. `docker-compose down -v`
6. Edit nginx.conf and restart container
