# Docker: netperf

Dockerfile packaging [netperf](http://www.netperf.org/). Original source based off of [tgraf/netperf-dockerfile](https://github.com/tgraf/netperf-docker).

### Download Image
```sh
docker pull alectolytic/netperf
```

### netserver usage
```sh
docker run -d --name netserver alectolytic/netperf
```

###  netperf usage
```sh
docker run --run --rm -it alectolytic/netperf netperf --help
```

