# docker-grib2json
Dockerized cambecc/grib2json
```
docker run --name grib2json --rm -v /mnt/data:/usr/local/data -e "ARGS=--names --data --fp 2 --fs 103 --fv 10.0 --output /usr/local/data/output.json /usr/local/data/gfs.t18z.pgrbf00.2p5deg.grib2" alexwoif/docker-grib2json
```
