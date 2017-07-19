### Run for get a bash for run compose and artisan migrate make, etc
docker-compose run web /bin/bash
#### before down a docker-machine, connect with ssh and sync your db to hosthome path
rsync -azv db/ /hosthome/user/db/
