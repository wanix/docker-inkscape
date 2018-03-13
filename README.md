[![Docker Pulls](https://img.shields.io/docker/pulls/wanix/inkscape.svg)](https://hub.docker.com/r/wanix/inkscape/)
[![Docker Stars](https://img.shields.io/docker/stars/wanix/inkscape.svg)](https://hub.docker.com/r/wanix/inkscape/)
[![GitHub tag](https://img.shields.io/github/tag/wanix/docker-inkscape.svg?maxAge=2592000)]()
[![](https://badge.imagelayers.io/wanix/inkscape:latest.svg)](https://imagelayers.io/?images=wanix/inkscape:latest)

# docker-inkscape #
docker container with Inkscape inside to execute CI batches

Volume given is /srv/inkscape

## Example ##

``` shell
docker run --rm -v $PWD/example:/srv/inkscape wanix/inkscape inkscape -z -e /srv/inkscape/test.png /srv/inkscape/test.svg
```

## building ##

``` shell
git clone https://github.com/wanix/docker-inkscape.git 
cd docker-inkscape
docker build -t wanix/inkscape .
```

## Licence ##
[Apache Licence V2](LICENSE)
