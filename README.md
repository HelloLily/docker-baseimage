# HelloLily Base Image

HelloLily Base Image is a Docker image for
Python 2.7 based on Alpine Linux.

## Included Software

- git
- python2.7
- pip
- gcc/musql/linux-headers
- nodejs
- postgresql-dev
- libmaxminddb
 - libffi-dev

## Building and pushing the image

```shell
$ docker build . -t hellolily/baseimage:latest
$ docker push hellolily/baseimage:latest
```

## Credits

- [João Ferreira Loff](https://github.com/jfloff) for building an awesome Python image which inspired this image.
