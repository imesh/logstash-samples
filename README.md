### Logstash Samples

This repository includes logstash samples:

   - Log4j + JMX Sample
   
####How to run:

   - Download logstash, elastic search, kibana distributions from elastic.co: 
     https://www.elastic.co/products
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
