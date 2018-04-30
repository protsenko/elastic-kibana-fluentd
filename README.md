Version of docker-compose is 3.3. Docker engine has to be upgraded for version 17.06.0
or higher. Full list of version [here](https://docs.docker.com/compose/compose-file/compose-versioning/).

If you run the containers with 
[Oracle VirtualBox](https://www.virtualbox.org/)
you have to start your virtual machine with 4Gb RAM preferably.

Also the virtual machine must be configured with vm.max_map_count option.
Have a look at [docs](https://www.elastic.co/guide/en/elasticsearch/reference/current/vm-max-map-count.html).
```
docker-machine ssh
sudo sysctl -w vm.max_map_count=262144
```
