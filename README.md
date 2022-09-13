# Apache Flink Clıster with Zookeeper and Kafka

**Flink Properties** 

Properties written for high availibility cluster. While one or more job running on a task manager and if the task manager stops for some reason the job will be continiued after delay.
You can change the delay time with *restart-strategy.fixed-delay* also you can change the attempts with *restart-strategy.fixed-delay.attempts*.
You can make changes depending on how many task managers you want to work with just change the *scale*.
