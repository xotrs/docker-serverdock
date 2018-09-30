FROM logstash:latest
LABEL key="cherrypick <xotrs1@gmail.com>"

RUN rm -f /usr/share/logstash/pipeline/logstash.conf
RUN /usr/share/logstash/bin/logstash-plugin install logstash-input-file && \
 /usr/share/logstash/bin/logstash-plugin install logstash-filter-json
ADD pipeline/ /usr/share/logstash/pipeline/
ADD config/ /usr/share/logstash/config/
