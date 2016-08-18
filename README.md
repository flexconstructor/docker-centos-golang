# docker-centos-golang
Docker image for easy start-up of Go programs on centos 7.
We conclude the following: 
* supervisor
* golang 1.7
* go-wrapper.sh from https://github.com/docker-library/golang.git

For load dependency:
```
$ docker-wrapper download [dependency libs]
```
For install dependency:
```
$ docker-wrapper install [dependency libs]
```
Fo run goprogramm:
```
$ docker-wrapper run
```

