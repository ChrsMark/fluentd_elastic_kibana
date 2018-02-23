# fluentd_elastic_kibana
Dockerized Fluentd-Elastic-Kibana stack for container monitoring

* Run the stack with `docker-compose -f docker-compose.yml -f example/httpd.yml up`  (you may need `chmod 777 -R es` in order to avoid permission errors and `sudo sysctl -w vm.max_map_count=262144` to resolve heap size problems)
* Then access `http://<IP>:5601` to visit Kibana page.
* Set the index to `fluentd-*`.


* To produce logs visit the dummy server on `http://<IP>`
