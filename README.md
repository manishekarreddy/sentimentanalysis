# sentimentanalysis

how to start project.

1. build and run docker image for kafka producer.
2.  cd tweets_producer.
3.  docker build -t tp .
4.  docker run tp
5. This will stream tweets the tweets to kafka topic

6. docker compose file is configured to run the spark application, backend server and web application
7. can be executed through
1. **execution.bat or execution.sh**
