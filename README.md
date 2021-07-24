# Exchange-Trading-DevOps
It's repositorium which include all configurations needed to build and run Exchange-Trading project.  
There are:
- docker_compose.yml
- prometheus.yml
- jvm_dashboard.json

## Docker_compose.yml
This file contains all configurations for Exchange-Trading. There are defined containers of:
- Exchange-Trading-Api -> Exchange-Trading backend (https://hub.docker.com/repository/docker/pkwasek/et-api)
- Exchange-Trading-Tester -> application which simulates behavoiur of real stock exchange (https://hub.docker.com/repository/docker/pkwasek/et-tester)
- Exchange-Trading-App -> Exchange-Trading frontend (https://hub.docker.com/repository/docker/pkwasek/et-angular-app)
- PostgreSQL databases (using for Exchange-Trading-Api and Exchange-Trading-Tester)
- Prometheus -> app to monitor system resources
- Grafana -> app to display plots in real time  

Links to related repositories was attached below.

## prometheus.yml
There are configuration which is needed to connect Prometheus with Exchange_Trading application.

## jvm_dashboard.json
This file is included when online import of dashbord doesn't work, then user must import this json file in Grafana.

## Linked repositoris
* [Exchange-Trading-Api](https://github.com/pkwasek08/Exchange-Trading)  
* [Echange-Trading-App](https://github.com/pkwasek08/Exchange-Trading-App)  
* [Echange-Trading-Tester](https://github.com/pkwasek08/Exchange-Trading-Tester)  