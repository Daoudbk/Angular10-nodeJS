## Database mongo
* Start database : 

docker-compose -f app/docker/docker-compose.yml up -d

* Restart database : 

docker-compose -f app/docker/docker-compose.yml restart

* Stop database : 

docker-compose -f app/docker/docker-compose.yml down

* Stop database : 

docker-compose -f app/docker/docker-compose.yml up --build --force-recreate --renew-anon-volumes

* STOP ALL CONTAINERS

docker stop $(docker ps -a -q)



