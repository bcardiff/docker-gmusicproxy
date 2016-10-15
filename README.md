# GMusicProxy
### Base Image: [`python:2`](https://registry.hub.docker.com/_/python)

#### Example
```
$ docker run --name gmusicproxy -v /PATH/TO/gmusicproxy.cfg:/etc/gmusicproxy.cfg \
    -p 80:80 digitallyseamless/gmusicproxy --config=/etc/gmusicproxy.cfg
```

#### gmusicproxy.cfg

In order for the above `docker run` command to work the following `gmusicproxy.cfg` is needed.

```
email = your-email-address@gmail.com
password = secret-app-password
device-id = some-random-uuid-or-your-mac-address
host = localhost
port = 80
```

Read more config options at [gmusicproxy.net](http://gmusicproxy.net/#gmusicproxy-google-play-music-proxy-usage-config-file).

