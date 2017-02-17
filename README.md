# docker-microservice

> cd docker-img

build docker image
> docker build -t service .
...

run server echo service
> docker run -d -p 8000:8000 service

5c1a0120a2480814f440f26a33458d35e8ef6e663736e57ae4d46cf042843b7a

list current docker containers
> docker ps

CONTAINER ID        IMAGE               COMMAND              CREATED             STATUS              PORTS                    NAMES

5c1a0120a248        service             "python server.py"   2 minutes ago       Up 2 minutes        0.0.0.0:8000->8000/tcp   naughty_murdock

in another terminal run the client
> python client.py

Server said: hello, world!

connection lost

Connection lost - goodbye!

