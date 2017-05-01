# curl
Just curl in a container

```
alias curl="docker run --rm -v /var/run/docker.sock:/var/run/docker.sock jsecchiero/curl curl"
curl --version
```

for armhf
```
alias curl="docker run --rm -v /var/run/docker.sock:/var/run/docker.sock jsecchiero/curl_armhf curl"
curl --version
```
