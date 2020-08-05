# TorrServer (by YouROK) Dockerfile

## Usage

```
docker run -d \
	-p 8090:8090 \
	-v torrserver-data:/torrserver \
	--restart unless-stopped \
	--name torrserver-amd64 \
	Nuke142/torrserver-amd64
```

## Parameters

* `-p 8090:8090` - TorrServer port
* `-v torrserver-data:/torrserver` - where TorrServer store config files
* `--name torrserver-amd64` - container name

## Info

* To monitor the logs of container in realtime `docker logs torrserver-amd64`

## Versions
+ **06.08.2020:** TorrServer ver. 1.1.7
+ **28.05.2020:** TorrServer ver. 1.1.76_24
+ **15.02.2020:** TorrServer ver. 1.1.76_9
+ **03.02.2020:** TorrServer ver. 1.1.76_7
+ **29.01.2020:** TorrServer ver. 1.1.76_5
