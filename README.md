# NginX Labs

---

#### Basic initial instructions

Build image from dockerfile:
 `docker build -f dockerfiles/Dockerfile_nginx -t my_nginx:001 .`

Run container:
 `docker run --rm --name nginx_container -it -p 8079:80 my_nginx:001`

In your browser, go to `127.0.0.1:8079/`. You should see "Welcome to NginX" page.

