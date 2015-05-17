# GMusicProxy
### Base Image: [`python:2`](https://registry.hub.docker.com/_/python)

#### Example
```
$ docker run --name gmusicproxy -v /PATH/TO/gmusicproxy.cfg:/etc/gmusicproxy.cfg \
    -p 80:80 digitallyseamless/gmusicproxy --config=/etc/gmusicproxy.cfg
```
