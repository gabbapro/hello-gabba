# Hello, Gabba!
A simple hello world web server
___
Scope of this container is to run a simple web server with a fixed page, containing references to the Cloud Native workshop series. The resulting Web page is based on a Blogin template (courtesy of www.blogin.co).
___
## git clone
```
git clone http://github.com/gabbapro/hello-gabba
```
___
## docker build
```
docker build . -t gabba/hello-gabba:latest
```
___
## docker run
```
 docker run -d --name hello-gabba -p 8011:8000 gabba/hello-gabba:latest
```
___
 
