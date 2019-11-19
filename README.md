# TorrServer (by YouROK) Dockerfile

## Usage

```
docker run -d \
	-p 8090:8090 \
	-v torrserver-data:/torrserver \
	--restart always \
	--name torrserver-amd64 \
	choodique/torrserver-amd64
```

## Parameters

* `-p 8090:8090` - TorrServer port
* `-v torrserver-data:/torrserver` - where TorrServer store config files
* `--name torrserver-amd64` - container name

## Info

* To monitor the logs of container in realtime `docker logs torrserver-amd64`

## Versions
+ **19.11.2019:** TorrServer ver. 1.1.76_1
+ **04.11.2019:** TorrServer ver. 1.1.76
+ **14.10.2019:** TorrServer ver. 1.1.75
+ **17.07.2019:** TorrServer ver. 1.1.69
