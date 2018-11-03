# hpts-docker
hpts(http-proxy-to-socks) proxy running in a docker container

## Usage
docker run -d grinco/hpts -e SOCKS_SERVER='127.0.0.1:1080' -e PROXY_PORT='8080' -p 8080:8080
