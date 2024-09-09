docker run -d --restart=always --name mosdns --net=host -e TZ=Asia/Shanghai -v /volume1/docker/mosdns:/etc/mosdns irinesistiana/mosdns:latest
