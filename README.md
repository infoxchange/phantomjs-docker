PhantomJS in a container
========================
Execute PhantomJS without worring about dependencies.


How to build
============
```bash
docker build -t phantomjs-docker .
```


Usage
=====
*Check version*
```bash
docker run --rm phantomjs-docker -v
```

*REPL mode*
```bash
docker run --rm -it phantomjs-docker
```
