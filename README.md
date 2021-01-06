# docker-php-kafka
docker image for php kafka

* Run the docker container using docker-compose.yml file

* There are two sample files i.e producer.php (To produce message to Kafka queue). To execute this file just go to your browser and open
  http://localhost:8089/producer.php?test=message

  This will pass the query string i.e "test=message" to Kafka queue
  
* The other sample file is consumer.php to consume or read the Kafka queue message. To check the Kafka queue message, go to terminal 
  and execute your "drupal" container. Then run command
  root@3b06698c6840:/var/www# php consumer.php
  
  This will show your kafka queue message at real time.
