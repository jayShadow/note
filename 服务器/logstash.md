```shell script
docker run -d --restart=always ^
--log-driver json-file ^
--log-opt max-size=100m ^
--log-opt max-file=2 ^
-p 5044:5044 ^
-p 9600:9600 ^
--name logstash ^
-v /d/docker_volumes/logstash/logstash.yml:/usr/share/logstash/config/logstash.yml ^
-v /d/docker_volumes/logstash/pipeline/logstash.conf:/usr/share/logstash/pipeline/logstash.conf ^
logstash:7.8.0
```



```shell script
docker run -d --restart=always ^
--log-driver json-file ^
--log-opt max-size=100m ^
--log-opt max-file=2 ^
--name kibana ^
-p 5601:5601 ^
-v /d/docker_volumes/kibana/kibana.yml:/usr/share/kibana/config/kibana.yml ^
kibana:7.8.0
```