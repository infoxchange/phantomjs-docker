PhantomJS in a container
========================
Execute PhantomJS without worring about dependencies.

## Build Image

You can manually build image by below commands.

```
$ git clone https://github.com/infoxchange/phantomjs-docker.git
$ cd phantomjs-docker
$ docker build -t infoxchange/phantomjs-docker .
```

It take so long to complete install process. You can also pull image from docker hub.

```
$ docker pull infoxchange/phantomjs-docker
```

## Check version

```
$ docker run --rm -it infoxchange/phantomjs-docker --version
1.9.8
```

## Run REPL

```
$ docker run --rm -it infoxchange/phantomjs-docker
phantomjs>
```
