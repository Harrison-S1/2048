# 2048
The game 2048

Code of 2048 is by (gabrielecirulli/2048)[https://github.com/gabrielecirulli/2048]
This is just a docker version of 2048, based on the nginx image.

## Pull from docker hub

```bash
docker pull harrisons1/2048
```

## OR

## Build yourself

```bash
git clone https://github.com/Harrison-S1/2048.git && cd 2048
```

```bash
docker build . -t "2048"
```
```bash
docker run -d -p 8080:80 2048
```

## Access

```bash
http://127.0.0.1:8080
```
