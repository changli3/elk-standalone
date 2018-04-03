# elk-standalone
A standalone ELK script. Run link this -
```
curl -s -L https://raw.githubusercontent.com/changli3/elk-standalone/master/install.sh | bash
```

The script will install and setup:
* elasticSearch: running on port 9200. Go to http://ip_address:9200 to test elasticSearch api
* kibina: running on port 5601. Go to http://ip_address:5601 to test kibina elasticSearch
* logStash server: running on port 5044. Process received traffic and forward it to 
* filebeat: example of using filebeat to forward local system log files /var/log/message and /var/log/secure to the logStash server
* mongodb: running on 27017
* logStash client: example of running mongo db stats on two data collections and forward the data to elasticSearch using logstash
* packagebeat: example of using filebeat to forward mongodb traffic to elasticSearch
