FROM docker.elastic.co/elasticsearch/elasticsearch:5.4.1

LABEL key="cherrypick <xotrs1@gmail.com>" 

RUN \
  mv /usr/share/elasticsearch/plugins/x-pack /usr/share/elasticsearch/plugins/.removing-x-pack && \
  mv /usr/share/elasticsearch/plugins/.removing-x-pack /usr/share/elasticsearch/plugins/x-pack && \
  /usr/share/elasticsearch/bin/elasticsearch-plugin remove x-pack


RUN ./bin/elasticsearch-plugin install https://oss.sonatype.org/service/local/repositories/releases/content/org/bitbucket/eunjeon/elasticsearch-analysis-seunjeon/5.4.1.1/elasticsearch-analysis-seunjeon-5.4.1.1.zip

EXPOSE 9200 9300

