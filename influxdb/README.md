- docker stack deploy -c docker-stack.yml docker-monitor

create influx database 

- docker exec `docker ps | grep -i influx | awk '{print $1}'` influx -execute 'CREATE DATABASE cadvisor'

configure influx db from grafana gui


import dashboard
