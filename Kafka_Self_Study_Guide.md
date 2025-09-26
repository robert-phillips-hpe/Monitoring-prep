# Kafka Self-Study Course

## Course Overview
This self-study course is designed to provide a comprehensive understanding of Apache Kafka, its architecture, concepts, and practical usage. Whether you're an aspiring data engineer, software developer, or IT professional, this course will equip you with the skills to design Kafka-based solutions, manage Kafka clusters, and integrate Kafka with other systems.

### Course Outline
1. **Introduction to Apache Kafka**  
   - What is Kafka?  
   - Core concepts and use cases  
   - Kafka ecosystem overview  

2. **Kafka Architecture**  
   - Brokers, topics, partitions, and messages  
   - Producers, consumers, and consumer groups  
   - Replication and fault tolerance  

3. **Installing and Configuring Kafka**  
   - Setting up Kafka locally  
   - Configuration files and tuning properties  
   - Zookeeper role in Kafka  

4. **Producing and Consuming Data**  
   - Kafka Producer API  
   - Kafka Consumer API  
   - Serialization and deserialization  

5. **Kafka Streams and Connect**  
   - Introduction to Kafka Streams  
   - Building stream-based applications  
   - Kafka Connect for system integration  

6. **Monitoring and Managing Kafka**  
   - Kafka monitoring tools  
   - Metrics and logging  
   - Troubleshooting Kafka  

7. **Advanced Kafka Topics**  
   - Partitioning strategies  
   - Compaction and retention policies  
   - Kafka security (SSL, SASL, ACLs)  

8. **Hands-On Projects**  
   - Building a real-time messaging system  
   - Integrating Kafka with a database  
   - Streaming analytics with Kafka Streams  

### Prerequisites and Required Skills

To get the most out of this course, you should have the following prerequisites:
1. **Basic Programming Knowledge**  
   - Familiarity with any programming language (e.g., Java, Python, or Go).  
     *Source: [Learn Java](https://www.learnjavaonline.org), [Python Basics](https://www.python.org/about/gettingstarted/)*  

2. **Understanding of Distributed Systems**  
   - Basic knowledge of distributed systems concepts (e.g., nodes, clusters, replication).  
     *Source: [Fundamentals of Distributed Systems](https://www.baeldung.com/cs/distributed-systems-guide)*  

3. **Basic Networking Knowledge**  
   - Understanding of TCP/IP, ports, and network protocols.  
     *Source: [Linux Networking Tutorials](https://www.baeldung.com/linux/networking-series)*  

4. **Experience with Linux Command Line**  
   - Ability to navigate and execute commands in a Linux terminal.  
     *Source: [Linux Command Line Basics](https://linuxcommand.org/)*  

5. **Knowledge of Databases**  
   - Familiarity with relational and non-relational databases.  
     *Source: [Basic Database Concepts](https://www.geeksforgeeks.org/computer-science-fundamentals/basic-database-concepts/)*  

---

### Module Details, Exercises, and Online Resources

#### Module 1: Introduction to Apache Kafka  
**Time Frame:** 3 hours  
**Topics Covered:**  
- Overview of Kafka’s history and purpose  
- Kafka as a distributed messaging system  
- Common use cases: event streaming, log aggregation, real-time analytics  

**Exercises:**  
1. Research three companies using Kafka and describe their use cases.  
2. Write a short essay on how Kafka improves data pipelines compared to traditional systems.  

**Resources:**  
- [Apache Kafka Official Documentation](https://kafka.apache.org/documentation/)  
- [Confluent’s Kafka Overview](https://www.confluent.io/what-is-apache-kafka/)  
- [Top 10 Kafka Use Cases](https://blog.algomaster.io/p/top-10-kafka-use-cases)  

---

#### Module 2: Kafka Architecture  
**Time Frame:** 5 hours  
**Topics Covered:**  
- Kafka brokers, topics, and partitions  
- Producers and consumers  
- Consumer groups and message delivery guarantees  

**Exercises:**  
1. Draw a diagram illustrating Kafka architecture with brokers, topics, partitions, producers, and consumers.  
2. Explain the role of consumer groups in load balancing and fault tolerance.  

**Resources:**  
- [Kafka Architecture](https://www.geeksforgeeks.org/apache-kafka/kafka-architecture/)  
- [Intro to Apache Kafka: Tutorials, Explainer Videos & More](https://developer.confluent.io/what-is-apache-kafka/)  

---

#### Module 3: Installing and Configuring Kafka  
**Time Frame:** 6 hours  
**Topics Covered:**  
- Setting up Kafka and Zookeeper locally  
- Understanding configuration properties  

**Exercises:**  
1. Install Kafka on your local machine following official documentation.  
2. Configure Kafka to use a custom log directory.  

**Resources:**  
- [Kafka Installation Guide](https://docs.confluent.io/platform/current/quickstart/index.html)  
- [Zookeeper Basics](https://zookeeper.apache.org/doc/current/zookeeperStarted.html)  

---

#### Module 4: Producing and Consuming Data  
**Time Frame:** 8 hours  
**Topics Covered:**  
- Kafka Producer API  
- Kafka Consumer API  
- Serialization and deserialization strategies  

**Exercises:**  
1. Write a Java or Python producer program to send messages to a Kafka topic.  
2. Write a consumer program to read those messages.  

**Resources:**  
- [Kafka Producer API Documentation](https://kafka.apache.org/documentation/#producerapi)  
- [Kafka Consumer API Documentation](https://kafka.apache.org/documentation/#consumerapi)  
- [Apache Kafka Serializer and Deserializer](https://www.geeksforgeeks.org/java/apache-kafka-serializer-and-deserializer/)  

---

#### Module 5: Kafka Streams and Connect  
**Time Frame:** 10 hours  
**Topics Covered:**  
- Introduction to Kafka Streams  
- Kafka Connect for integrating with external systems  

**Exercises:**  
1. Build a simple Kafka Streams application to filter messages based on criteria.  
2. Use Kafka Connect to ingest data from a MySQL database.  

**Resources:**  
- [Kafka Streams Documentation](https://kafka.apache.org/documentation/streams/)  
- [Kafka Connect Documentation](https://kafka.apache.org/documentation/#connect)  

---

#### Module 6: Monitoring and Managing Kafka  
**Time Frame:** 7 hours  
**Topics Covered:**  
- Using monitoring tools like Prometheus and Grafana  
- Understanding Kafka metrics  

**Exercises:**  
1. Set up Prometheus and Grafana to monitor a Kafka cluster.  
2. Identify and solve a hypothetical issue using Kafka metrics.  

**Resources:**  
- [Monitoring Kafka with Prometheus](https://www.robustperception.io/monitoring-kafka-with-prometheus)  
- [Grafana Setup](https://grafana.com/docs/grafana/latest/setup-grafana/)  

---

#### Module 7: Advanced Kafka Topics  
**Time Frame:** 12 hours  
**Topics Covered:**  
- Partitioning strategies  
- Compaction and retention policies  
- Kafka security  

**Exercises:**  
1. Configure Kafka to use SSL for encrypted communication.  
2. Design a partitioning strategy for a hypothetical use case.  

**Resources:**  
- [Understanding Kafka Topics and Partitions](https://www.baeldung.com/kafka-topics-partitions)  
- [Kafka Security Guide](https://medium.com/@bhattchitrangna/securing-your-kafka-a-beginners-guide-to-kafka-security-ab2978a4d82e)  

---

#### Module 8: Hands-On Projects  
**Time Frame:** 20 hours  
**Topics Covered:**  
- Building real-world Kafka applications  

**Exercises:**  
1. Build a real-time messaging system using Kafka.  
2. Integrate Kafka with a database for data ingestion and querying.  

**Resources:**  
- [Kafka Real-World Examples](https://dzone.com/articles/real-world-examples-and-use-cases-for-apache-kafka)  
- [Real-Time Data Streams: Building Analytics with Kafka and Spark](https://www.javacodegeeks.com/2025/09/real-time-data-streams-building-analytics-with-kafka-and-spark.html)

---

### Course Time Frame  
- Total Estimated Time: 71 hours  
- Recommended Weekly Study: 10 hours  
- Total Duration: Approximately 7 weeks

---

### Questions to Test Understanding  
1. What are the key components of Kafka architecture?  
2. How does Kafka ensure fault tolerance?  
3. Explain the difference between Kafka Streams and Kafka Connect.  
4. What is the role of Zookeeper in Kafka?  
5. Describe the process of configuring Kafka security.  

---

### Final Notes  
This course is designed for individuals looking to develop expertise in Apache Kafka. By following the modules and completing the exercises, you’ll gain hands-on experience and a deep understanding of Kafka’s capabilities.  
