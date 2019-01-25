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

# Why Kafka

+++

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

### Events describe what happened. 

### Sequences of events (streams) describe how it happened

+++

### Sequencing of moves is sometimes more important than end state


![streams](images/chessGame.png)

+++

### Stock price


![streams](images/stock.png)

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

* Kafka Topic

![logIdea](images/logIdea.png)

+++

### Consumer position

![consumerPosition](images/consumerLog.png)

+++

### Connectors

![kafkaConnectors](images/kafkaConnectors.png)

+++

### Sink/Source Connectors

![kafkaConnectors](images/sinkSource.png)

+++

### Input/Output to any data source

![kafkaConnectorsOut](images/kafkaConnectOutput.png)

+++

### Stream processing

![streamingEngine](images/streamingEngine.png)

+++

### Stream processing

* Query continuous data
* Detect conditions within a small time period
* Detection time varies from milliseconds to minutes
* Alternative names: real-time analytics, streaming analytics or event processing

+++

### Stream processing with combine and summarize


![streams](images/streamProcessing.png)

+++

### KSQL

![streamingEngine](images/ksql.png)

+++

### Windowed Aggregation

![timeFrames](images/windowTumbling.png)

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
* Provides ...
* ... distributed configuration service
* ... synchronization service
* ... naming registry


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
- Open-Source- Kafka on Kubernetes
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


![streams](images/softwareEvolution3.png)

+++

### Loosely coupled systems


![streams](images/softwareSystemEvolution2.png)

+++

### Real-time Event  Enrichment


![streams](images/realTimeEvents.png)

+++

### Evolve processing from old system to new


![streams](images/evolveProcessing.png)


---

## Demo

### Monitoring Dashboard

https://fast-data-dev.demo.landoop.com/

### Parsys Demo


---

# Thanks - QA?

---

### Sources
* [Confluent](https://www.confluent.io/)
* [Kafka](https://kafka.apache.org/)
* [Strimzi](https://strimzi.io/)
* [The Future of Applications is Streaming](https://www.ittage.informatik-aktuell.de)
* [Embrace the Anarchy](https://www.ittage.informatik-aktuell.de)
* [Apache Kafka - Data Streaming und Messaging in einem](https://www.ittage.informatik-aktuell.de)

### Literature
![reading](images/furtherReading.png)

