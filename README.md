# elk-standalone
A standalone ELK script. Run link this -
```
curl -s -L https://raw.githubusercontent.com/changli3/elk-standalone/master/install.sh | bash
```

The script will install and setup:
* elasticSearch (port 9200)
* kibina (port 5601 and 80)
* logStash (port 5044)
* filebeat (forward local /var/log/message and /var/log/secure to logStash)
* mongodb
