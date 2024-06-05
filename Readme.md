# Spatio temporal docker

Create a docker of the [Spatio Temporal project](https://github.com/VCityTeam/UD-Demo-IMU-Spatio-Temporal).  

The demo uses a [SimpleServer](https://github.com/VCityTeam/UD-SimpleServer), based on [ExpressJS](https://en.wikipedia.org/wiki/Express.js) web-server.

Clone the repo

```bash
git clone https://github.com/VCityTeam/UD-Demo-IMU-Spatio-Temporal-docker.git
cd UD-Demo-IMU-Spatio-Temporal-docker
```

Build the docker image with

```bash
docker build -t demo_st .
```

and run the container with

```bash
docker run -p 8000:80/tcp -t demo_st
```

and open a web browser on URL `http://localhost:8000/`
