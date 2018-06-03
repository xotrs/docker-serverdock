FROM docker.elastic.co/elasticsearch/elasticsearch:6.1.1

MAINTAINER Youngrok Lim <xotrs1@gmail.com>

RUN ./bin/elasticsearch-plugin install https://oss.sonatype.org/service/local/repositories/releases/content/org/bitbucket/eunjeon/elasticsearch-analysis-seunjeon/6.1.1.1/elasticsearch-analysis-seunjeon-6.1.1.1.zip

EXPOSE 9200 9300

