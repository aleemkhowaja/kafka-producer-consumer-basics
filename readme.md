Welcome to Spring Boot with Kafka and Docker Image

Following commands to be run in doicker

1 - Run this command for loading the docker-compose.yml file

sudo docker-compose -f docker-compose.yml up --build --force-recreate
                        OR

2 - Creating the topic in latest kafka in docker
./kafka-topics.sh --create --topic test-topic --bootstrap-server localhost:9092 --replication-factor 1 --partitions 4

