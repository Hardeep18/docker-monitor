- docker stack deploy -c docker-stack.yml docker-monitor

create influx database 

- docker exec (<containerID) influx -execute 'CREATE DATABASE cadvisor'

configure influx db from grafana gui


import dashboard
