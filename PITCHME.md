---
@title[Apache Kafka]

![Logo](images/kafkalogo.png)

---
@title[Overview]
### Overview
* Why Kafka
* What is Kafka
* Technical View
* Deployment View
* Target Architectures
* DEMO

---

@title[Why Kafka]

### How everything started ...
![dwh1](images/firstDwh.png)



+++
### We want more datasources

![dwh2](images/secondDwh.png)

+++

### Where we ended

![dwh2](images/complexArchitecture.png)

+++

### There was a guy ...

![dwh2](images/kafkaf.jpg)

+++

### Possible Solution

![dwh2](images/kafkaCentered.png)

---
@title[How does it work]

### Concepts

* Events
* Streaming
* Event-Driven Development

+++

### Events in everyday life

* Change Address - Move
* Marriage
* Get your driving license
* Start a new work

+++

### An event is

* Notification
* State transfer


+++

### Events come in streams


![streams](images/streams.png)

+++

### Stream processing with combine and summarize


![streams](images/streamProcessing.png)

+++

### Events describe what happened. 

### Sequences of events (streams) describe how it happened


---
@title[Kafka Components]

### Kafka components

* Components
* Log
* Connectors
* Stream processing

+++

### High level kafka

![streamingPlatform](images/streamingPlattform.png)

+++

### The distributed log

![kafkaLog](images/kafkaLog.png)

+++

### Idea of the log

![logIdea](images/logIdea.png)

+++

### Consumer position

![consumerPosition](images/consumerLog.png)

+++

### Connectors

![kafkaConnectors](images/kafkaConnectors.png)

+++

### Input/Output to any data source

![kafkaConnectorsOut](images/kafkaConnectOutput.png)

+++

### Stream processing

![streamingEngine](images/streamingEngine.png)

+++

### KSQL

![streamingEngine](images/ksql.png)

+++

### Java processing

![streamJava](images/streamProcessingJava.png)

---
@title[DeploymentView]

### Deployment View

* Kafka and zookeeper
* Strimzi

+++

### Apache Zookeeper

* Centralized service for distributed systems
* Provides distributed configuration service
* Provides synchronization service
* Provides naming registry


+++

### Role of zookeeper with kafka

![streamJava](images/clusterConfig.png)

+++

@snap[north]
![strimziLogo](images/strimzi.png)
@snapend

@snap[west sidebar]
![openshiftCluster](images/openshiftCluster.png)
@snapend

@snap[east sidebar]
@ul
- Open-Source running Kafka on Kubernetes
- Kafka as Kubernetes Resource
- Operator creates Kafka Cluster and Zookeeper
@ulend
@snapend

---
@title[Architectureal view]

### Architectural patterns

* Evolution of software systems
* Target architectures

+++

### Evolution of software systems


![streams](images/softwareSystemEvolution.png)

+++

### Evolution of software systems


![streams](images/softwareSystemEvolution2.png)

+++

### Target Architecture


![streams](images/softwareSystemEvolution2.png)

+++

### Confluent platform


![streams](images/confluentPlatform.png)

---

## Demo

### Monitoring Dashboard

https://fast-data-dev.demo.landoop.com/


---

# Thanks - QA?

---

### Sources
* [Confluent](https://www.confluent.io/)
* [4-Years of GraphQL](https://kafka.apache.org/)
* [GraphQL under the hood](https://about.sourcegraph.com/graphql/graphql-under-the-hood)
* [Eric-Baer-GraphQL under the hood](https://www.youtube.com/watch?v=fo6X91t3O2I)
* [graphql-java](https://github.com/graphql-java/graphql-java)
* [data-loader](https://medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433)

