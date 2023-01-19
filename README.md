# Logstash Docker Compose

## Instalaltion
1. Install docker and docker-compose on your machine
2. Git clone this directory to a folder
3. Go into the logstash-docker-compose directory and run the following command:
```
$ docker-compose up -d
```
4. Add your logstash config file to th directory: /var/lib/dockr/volumes/logstashdockercompose_logstash_conf/_data/

## Plugins Installed
 - logstash-output-jdbc
 - logstash-codec-netflow
 - logstash-filter-translate
 - logstash-filter-uuid
 - logstash-filter-cidr
 - logstash-filter-multiline
 - logstash-filter-tld
 - logstash-filter-elasticsearch
 - logstash-filter-rest
 - logstash-output-statsd
 - logstash-filter-metricize
 - logstash-filter-metrics
 - logstash-filter-fingerprint
 - logstash-input-rss
 - logstash-output-exec
