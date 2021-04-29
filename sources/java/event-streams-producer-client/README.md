# Producer client for IBM Event Streams

This Java application will send the data in the `tempdata.csv` file to IBM Event Streams.

Steps to run the application:
1. Build the application

Run the below command:
```
gradle clean build
```

2. Run the application

Run the below command:
```
java -jar ./build/libs/event-streams-producer-client-2.0.jar <kafka_brokers_sasl> <api_key> -producer
```

>Note: The kafka_brokers_sasl must be formatted as "host:port,host2:port2".
Format the contents of kafka_brokers_sasl in a text editor before entering it in the command line.
