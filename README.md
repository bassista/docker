<<<<<<< HEAD
# docker stuff


### Purpose

This repository stores my docker images and associated projects for **application development using containers** (currently docker).


### Architecture of Container Interactions
![AppDev Component Architecture with Docker](https://github.com/matallen/docker/blob/master/app-dev-component-arch.png "AppDev Component Architecture with Docker")

=======
## Graphite + Carbon + Statsd + Grafana + Elasticsearch

An all-in-one image running graphite and carbon-cache and grafana.

This image contains a sensible default configuration of graphite and
carbon-cache. Starting this container will, by default, bind the the following
host ports:

- `80`: the graphite web interface
- `81`: the grafana web interface
- `2003`: the carbon-cache line receiver (the standard graphite protocol)
- `2004`: the carbon-cache pickle receiver
- `7002`: the carbon-cache query port (used by the web interface)


´´´
./build

./start
´´´

modify start to map to the ports and host directories you need.

Modified from https://github.com/SamSaffron/graphite_dockertrue
>>>>>>> 59d963ed900008507c5d3439267ccb6d2eb097b6
