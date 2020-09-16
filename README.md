# elk-docker-compose
# Opendistro-elasticsearch 1.9.0
# Opendistro-kibana 1.9.0
# logstash-oss 7.8.1
# filebeat-oss 7.8.1

Step1: Clone ELK 

git clone https://github.com/hiep-hoang/elk-docker-compose.git

Step2: Move all in "elk-docker-compose" directory to "root" directory 

mv elk-docker-compose/* /root/

Step3: RUN docker compose to deploy elk 

docker-compose -f elk-compose.yml up

Step3: Config by your style ^^
