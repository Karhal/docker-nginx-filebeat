1. git clone https://github.com/Karhal/docker-elk.git
2. git clone https://github.com/Karhal/docker-nginx-filebeat.git
3. cd docker-nginx-filebeat
4. docker network create elk_network 
5. Start elk suite
6. docker network inspect elk_network
7. Change IP's in the filebeat.yml
8. Go to kibana -> Discover -> Create Dataview
