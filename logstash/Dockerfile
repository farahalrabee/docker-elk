# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-x-pack:6.0.0

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-jdbc
RUN logstash-plugin install logstash-filter-mutate
RUN logstash-plugin install logstash-filter-aggregate
RUN logstash-plugin install logstash-filter-sleep
