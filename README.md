# docker_awx

Docker compose configuration for [AWX](https://github.com/ansible/awx). Ready
for deployment with
[Puppet](https://github.com/naturalis/puppet-docker_compose).

## Docker-compose

Docker-compose definition for deployment of Naturalis AWX server. Which consists
of:

* `postgres`
* `rabbitmq`
* `memcached`
* `awx_web`
* `awx_task`
* `traefik`

## Result

Working AWX server available on
[awx.museum.naturalis.nl](https://awx.museum.naturalis.nl).

## Limitations

Deployment has been tested on Ubuntu 18.04.
