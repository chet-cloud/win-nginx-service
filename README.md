# Web server in windows

1. run nginx as a server
2. checkout https://github.com/sheggi/win-service-nginx
3. checkout https://github.com/winsw/winsw


# Usage

1. Clone the proejct into c:/

```shell
git clone https://github.com/chet-cloud/win-nginx-service.git c:/nginx
```

2. Install, start, stop, status, and restart the service

    - open cmd.exe and switch to the directory - c:/nginx

    - input the following commands

```shell
    nginx-service install
    nginx-service start
    nginx-service stop
    nginx-service status
    nginx-service restart
```

or You can open the Services (win+run>services.msc) and operate on nginx service after install the service