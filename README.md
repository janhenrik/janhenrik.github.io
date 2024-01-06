# Homepage

gundelsby.com

## Local Development

This repo includes a docker-compose file that allows you to quickly setup a container running Jekyll. If you don't already have Docker and docker-compose installed, you can install them using the following guides:

**Install Guides**
* [Docker](https://docs.docker.com/get-docker/)
* [docker-compose](https://docs.docker.com/compose/install/)

To start the container simply run:

```
docker-compose up
```

Alternatively you can run the container without docker-compose using this command on iOS/Linux:

```
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

# Credits
Based on [cvless](https://github.com/piazzai/cvless)
