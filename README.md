# KafkaTester

This cool tool will send a message to a kafka topic and see if it can read it.

Features:
 - Be able to specify configurations and test cases in  a yaml file
 
# Using kafkaTester

### Running Kafka

```bash
./gradlew minikubeStart deployKafkaToKube 
# or
./gradlew mS dKTK
```