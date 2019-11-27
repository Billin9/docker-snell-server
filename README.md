## Snell Server For Docker


### 运行

直接运行

```shell
docker run -d --name snell-server -p 80:8080 billin9/docker-snell-server:latest
```

> 默认 PSK 为: as1ffVD7ZpXmaQpsF1DnAs4ICNo0h3U

设置自己的 PSK

```shell
docker run -d --name snell-server -e PSK=$yourpsk -p 80:8080 billin9/docker-snell-server:latest
```
