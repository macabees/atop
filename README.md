# Atop (Performance Monitor)
Atop is an ASCII full-screen performance monitor for Linux that is capable of reporting the activity of all processes, with logging.

## Atop (Project Info)
[Website](https://www.atoptool.nl/)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/atop/)

## Build image
`$ docker build -t macabees/atop:latest .`

## Docker Push
`$ docker push -t macabees/atop:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm --name atop --pid=host macabees/atop`

## Help
docker run -it --rm macabees/atop --help

