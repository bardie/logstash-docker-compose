# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:8.6.0
USER logstash
# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN /usr/share/logstash/bin/logstash-plugin install logstash-output-jdbc logstash-codec-netflow logstash-filter-translate logstash-filter-uuid logstash-filter-cidr logstash-filter-multiline logstash-filter-tld logstash-filter-elasticsearch logstash-filter-rest logstash-output-statsd logstash-filter-metricize logstash-filter-metrics logstash-filter-fingerprint logstash-input-rss logstash-output-exec
