start Logstash: logstash -f ~/highload/assignment3/allMart/logstash.conf  
Elasticsearch:  sudo systemctl restart elasticsearch port 9200
Kibana:  sudo systemctl restart kibana port 5601
Prometheus: ./prometheus --config.file=prometheus.yml   port 9090\
Grafana: port 3000

