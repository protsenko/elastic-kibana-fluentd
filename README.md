If you run the containers with 
[Oracle VirtualBox](https://www.virtualbox.org/)
you must to start your virtual machine with 4Gb RAM at least.

Also the virtual machine must be configured with vm.max_map_count option.
```
docker-machine ssh
sudo sysctl -w vm.max_map_count=262144
```
Have a look at [docs](https://www.elastic.co/guide/en/elasticsearch/reference/current/vm-max-map-count.html).