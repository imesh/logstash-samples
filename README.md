### Logstash Samples

This repository includes logstash samples:

   - Log4j + JMX Sample
   
####How to run:

   - Download logstash, elastic search, kibana distributions from elastic.co: 
   
     ```
     wget https://download.elastic.co/elasticsearch/elasticsearch/elasticsearch-1.7.2.tar.gz
     wget https://download.elastic.co/kibana/kibana/kibana-4.1.2-linux-x64.tar.gz
     wget https://download.elastic.co/logstash/logstash/logstash-1.5.4.tar.gz
     ```
   - Extract and start elastic search and kibana
   - Extract logstash distribution and export LOGSTASH_HOME environment variable:
   
     ```
	 export LOGSTASH_HOME=/path/to/logstash
	 ```
   - Extract logstash distribution and install JMX plugin:
   
     ```
	 $LOGSTASH_HOME/bin/plugin install logstash-input-jmx
	 ```
   - Execute run.sh 
