## About The Project

- Apache Kafka Series - Learn Apache Kafka for Beginners v3
- START HERE: Learn Apache Kafka 3.0 Ecosystem, Core Concepts, Real World Java Producers/Consumers & Big Data Architecture
- [Stephane Maarek ](https://github.com/simplesteph)
- [Original Repo](https://github.com/conduktor/kafka-beginners-course)
- [conduktor](https://www.conduktor.io/)
- [Course Resources](https://www.conduktor.io/apache-kafka-for-beginners)

&nbsp;

---

&nbsp;

## Introduction

![source-systems-target-systems](/diagrams/source-systems-target-systems.png)

- If you have 4 **source systems**, and 6 **target systems**, you need to write 24 **integrations**
- Each integration comes with difficulties around
  - **Protocol:** how the data is transported (TCP, HTTP, REST, FTP, JDBC)
  - **Data format:** how the data is parsed (Binary, CSV, JSON, Avro, Protobuf)
  - Data schema & evolution: how the data is shaped and may change
- Each source system will have an increased load from the connections

![decoupling-of-data-streams-and-systems](/diagrams/decoupling-of-data-streams-and-systems.png)

&nbsp;

![decoupling-of-data-streams-and-systems-2](/diagrams/decoupling-of-data-streams-and-systems-2.png)

## Use-cases

- **Kafka is only used as a transportation mechanism**
- Messaging System
- Activity Tracking
- Gather metrics from many different locations
- Application Logs gathering
- Stream processing (with the Kafka Streams API for example)
- De-coupling of system dependencies
- Integration with Spark, Flink, Storm, Hadoop, and many other Big Data technologies
- Micro-services pub/sub

![course-outline](/diagrams/course-outline.png)

&nbsp;

---

&nbsp;
