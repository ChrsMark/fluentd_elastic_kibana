# fluentd_elastic_kibana
Dockerized Fluentd-Elastic-Kibana stack for container monitoring

Run the stack with `docker-compose -f docker-compose.yml -f example/httpd.yml up`
Then access `http://<IP>:5601` to visit Kibana page.
Set the index to `fluentd-*`.


To produce logs visit the dummy server on `http://<IP>
