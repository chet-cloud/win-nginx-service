# kisok server

1. run nginx as a server for the kiosk pages
2. checkout https://github.com/sheggi/win-service-nginx
3. checkout https://github.com/winsw/winsw


# Usage

1. Clone the proejct into c:/

git clone https://github.com/chet-cloud/win-nginx-service.git -o c:/nginx


2. install the service

open cmd.exe and switch to the directory - c:/nginx


- nginx-service install
- nginx-service start
- nginx-service stop
- nginx-service status
- nginx-service restart

or You can open the Services (win+run>services.msc) and start Nginx after install the service