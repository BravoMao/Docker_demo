# Docker_demo
A simple docker demo(docker build image/docekr run etc)


Docker build
----------
    $ docker build -t jianil/pingpong .


Docker run
----------
    $ docker run -d -p 8080:8080 jianil/pingpong


Test
----------
    $ curl http://localhost:8080/ping(linux)


