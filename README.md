# hpts-docker
hpts(http-proxy-to-socks) proxy running in a docker container

## Usage
For some reason I couldn't make it work reading the settings from ENV variables, so for now run it like that:
docker run --rm -p 8000:8000 grinco/hpts hpts -s 127.0.0.1:1080 -p 8000
