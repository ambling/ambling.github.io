---
layout: page
title: Recommands
permalink: /recommands/
---

### Apache Spark
- **Memory management**

	- [APACHE SPARK : MEMORY MANAGEMENT AND GRACEFUL DEGRADATION](https://ogirardot.wordpress.com/2014/12/11/apache-spark-memory-management-and-graceful-degradation/)

	- [Project Tungsten: Bringing Spark Closer to Bare Metal](https://databricks.com/blog/2015/04/28/project-tungsten-bringing-spark-closer-to-bare-metal.html)  
		1. **Memory Management and Binary Processing:** leveraging application semantics to manage memory explicitly and eliminate the overhead of JVM object model and garbage collection.  
		2. **Cache-aware computation:** algorithms and data structures to exploit memory hierarchy.  
		3. **Code generation:** using code generation to exploit modern compilers and CPUs.

  - [Deep Dive: Memory Management in Apache Spark](http://www.slideshare.net/databricks/deep-dive-memory-management-in-apache-spark)

    - [Tuning Java Garbage Collection for Spark Applications](https://databricks.com/blog/2015/05/28/tuning-java-garbage-collection-for-spark-applications.html)

- **Performance**

    - [How-to: Tune Your Apache Spark Jobs (Part 1)](http://blog.cloudera.com/blog/2015/03/how-to-tune-your-apache-spark-jobs-part-1/), [How-to: Tune Your Apache Spark Jobs (Part 2)](http://blog.cloudera.com/blog/2015/03/how-to-tune-your-apache-spark-jobs-part-2/)

    - [Top 3 Troubleshooting Tips To Keep You Sparking](https://engineering.sharethrough.com/blog/2013/09/13/top-3-troubleshooting-tips-to-keep-you-sparking/)

- **Tutorials and Courses**
  - [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/content/)
  - [AMP Camp Big Data Bootcamps](http://ampcamp.berkeley.edu/big-data-mini-course/)
	- [How to log in Apache Spark](https://medium.com/@anicolaspp/how-to-log-in-apache-spark-f4204fad78a#.sekwmyngq)
	- [Large-Scale Systems](http://people.csail.mit.edu/matei/courses/2015/6.S897/)
  - [Introduction to Apache Spark](https://www.edx.org/course/introduction-apache-spark-uc-berkeleyx-cs105x)
  - [Data Science and Engineering with Apache Spark](https://www.edx.org/xseries/data-science-engineering-apache-spark)
  - [Working with Complex Data Formats with Structured Streaming in Apache Spark 2.1](https://databricks.com/blog/2017/02/23/working-complex-data-formats-structured-streaming-apache-spark-2-1.html)

- **Others**
  - [A Tale of Three Apache Spark APIs: RDDs, DataFrames, and Datasets. When to use them and why](https://databricks.com/blog/2016/07/14/a-tale-of-three-apache-spark-apis-rdds-dataframes-and-datasets.html)
  - [Continuous Applications: Evolving Streaming in Apache Spark 2.0](https://databricks.com/blog/2016/07/28/continuous-applications-evolving-streaming-in-apache-spark-2-0.html)
  - [Structured Streaming In Apache Spark](https://databricks.com/blog/2016/07/28/structured-streaming-in-apache-spark.html)
  - [Spark Architecture: Shuffle](https://0x0fff.com/spark-architecture-shuffle/)

### Streaming
- [MICROBENCHMARKING APACHE STORM 1.0 PERFORMANCE](http://hortonworks.com/blog/microbenchmarking-storm-1-0-performance/)
- [High-throughput, low-latency, and exactly-once stream processing with Apache Flink](http://data-artisans.com/high-throughput-low-latency-and-exactly-once-stream-processing-with-apache-flink/)
- Comparison of Apache Stream Processing Frameworks: [Part 1](http://www.cakesolutions.net/teamblogs/comparison-of-apache-stream-processing-frameworks-part-1), [Part 2](http://www.cakesolutions.net/teamblogs/comparison-of-apache-stream-processing-frameworks-part-2)
- [Carrier Payments Big Data Pipeline using Apache Storm](https://www.paypal-engineering.com/2016/11/15/carrier-payments-big-data-pipeline-using-apache-storm/)
- [Introduction to Apache Flink](https://www.mapr.com/ebooks/intro-to-apache-flink/)
- [Throughput, Latency, and Yahoo! Performance Benchmarks. Is there a winner?](https://www.datatorrent.com/blog/throughput-latency-and-yahoo/)

### JAVA
- [Direct Memory Alignment in Java](http://psy-lob-saw.blogspot.jp/2013/01/direct-memory-alignment-in-java.html)
- [What every programmer should know about memory](http://lwn.net/Articles/250967/)
- [On Heap vs Off Heap Memory Usage](https://dzone.com/articles/heap-vs-heap-memory-usage)
- [G1: One Garbage Collector To Rule Them All](http://www.infoq.com/articles/G1-One-Garbage-Collector-To-Rule-Them-All)
- [Tips for Tuning the Garbage First Garbage Collector](http://www.infoq.com/articles/tuning-tips-G1-GC)
- [Garbage Collection Optimization for High-Throughput and Low-Latency Java Applications](https://engineering.linkedin.com/garbage-collection/garbage-collection-optimization-high-throughput-and-low-latency-java-applications)
- [Java Performance Tuning Guide: java.io.ByteArrayOutputStream](http://java-performance.info/java-io-bytearrayoutputstream/)
- [Java Performance Tuning Guide: Performance of various methods of binary serialization in Java](http://java-performance.info/various-methods-of-binary-serialization-in-java/)
- [Compact Strings In Java 9](https://www.javagists.com/compact-strings-java-9)

### Python
- [Understanding Python Decorators in 12 Easy Steps](https://dzone.com/articles/understanding-python)

### Distributed System
- [The Log: What every software engineer should know about real-time data's unifying abstraction](http://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)
- [Four Really Real Meanings of Real-Time](http://bigdatapage.com/4-really-real-meanings-of-real-time/)
- [AN OVERVIEW OF APACHE STREAMING TECHNOLOGIES](https://databaseline.wordpress.com/2016/03/12/an-overview-of-apache-streaming-technologies/)
- [A BRIEF HISTORY OF APACHE STORM](http://hortonworks.com/blog/brief-history-apache-storm/)
- [Understanding Consensus and Paxos in Distributed Systems](http://ifeanyi.co/posts/understanding-consensus/)
- [Inside Cloud Spanner and the CAP Theorem](https://cloudplatform.googleblog.com/2017/02/inside-Cloud-Spanner-and-the-CAP-Theorem.html)
- [Introducing Cloud Dataflow Shuffle: For up to 5x performance improvement in data analytic pipelines](https://cloud.google.com/blog/big-data/2017/06/introducing-cloud-dataflow-shuffle-for-up-to-5x-performance-improvement-in-data-analytic-pipelines)

### Machine Learning

- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)
- [Deep Learning](http://www.deeplearningbook.org/)
- [Practical Deep Learning For Coders](http://course.fast.ai/index.html)
- [The real prerequisite for machine learning isn’t math, it’s data analysis](https://www.r-bloggers.com/the-real-prerequisite-for-machine-learning-isnt-math-its-data-analysis/)

### Git
- [Git Tutorial by Liao Xuefeng in Chinese](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
- [Git Workflow by Ruan Yifeng in Chinese](http://www.ruanyifeng.com/blog/2015/12/git-workflow.html)
- [Git Use Process by Ruan Yifeng in Chinese](http://www.ruanyifeng.com/blog/2015/08/git-use-process.html)
- [Little Things I Like to Do with Git](https://csswizardry.com/2017/05/little-things-i-like-to-do-with-git/)

### About Trajectory Data
- [All 1.1 Billion Taxi Rides on Redshift](http://tech.marksblogg.com/all-billion-nyc-taxi-rides-redshift.html)
- Monitoring Real-Time Uber Data Using Spark Machine Learning, Streaming, and the Kafka API. [part 1](https://www.mapr.com/blog/monitoring-real-time-uber-data-using-spark-machine-learning-streaming-and-kafka-api-part-1), [part 2](https://www.mapr.com/blog/monitoring-real-time-uber-data-using-spark-machine-learning-streaming-and-kafka-api-part-2)
- [DETECTING ABUSE AT SCALE: LOCALITY SENSITIVE HASHING AT UBER ENGINEERING](https://eng.uber.com/lsh/)

### Insights
- [Expert Interview Series: IBM’s Holden Karau on Hadoop, ETL, Machine Learning and the Future of Spark](http://blog.syncsort.com/2016/06/big-data/ibms-holden-karau-on-hadoop-etl-machine-learning-and-the-future-of-spark/), [Part 2](http://blog.syncsort.com/2016/06/big-data/expert-interview-series-ibms-holden-karau-hadoop-etl-machine-learning-future-spark-part-2/)
- [Dataflow as Database](https://github.com/frankmcsherry/blog/blob/master/posts/2016-07-17.md)
- BI & Analytics on a Data Lake: [Part 1](https://www.mapr.com/blog/bi-analytics-and-big-data-%E2%80%9C-ha%E2%80%9D-moment-part-1), [Part 2](https://www.mapr.com/blog/exploring-relationship-between-hadoop-and-data-warehouse-part-2)
- [Hadoop Best Practices and Anti-Patterns](https://veekaybee.github.io/data-lake-talk/#/)
- [Server-side I/O Performance: Node vs. PHP vs. Java vs. Go](https://www.toptal.com/back-end/server-side-io-performance-node-php-java-go)
- [Enough with the microservices](https://aadrake.com/posts/2017-05-20-enough-with-the-microservices.html)
- [Can your CTO still code?](https://www.recode.net/2017/6/15/15332486/cto-code-coding-skills-developer-education-engineer)

### Tech Stack
- [THE UBER ENGINEERING TECH STACK, PART I: THE FOUNDATION](https://eng.uber.com/tech-stack-part-one/)
- [THE UBER ENGINEERING TECH STACK, PART II: THE EDGE AND BEYOND](https://eng.uber.com/tech-stack-part-two/)
- [How Uber Uses Spark and Hadoop to Optimize Customer Experience](https://www.datanami.com/2015/10/05/how-uber-uses-spark-and-hadoop-to-optimize-customer-experience/)
- PayPal From Big Data to Fast Data: [Part 1](https://www.paypal-engineering.com/2016/11/08/from-big-data-to-fast-data-in-four-weeks-or-how-reactive-programming-is-changing-the-world-part-1/), [Part 2](https://www.paypal-engineering.com/2016/11/18/from-big-data-to-fast-data-in-four-weeks-or-how-reactive-programming-is-changing-the-world-part-2/)

### Algorithms
- [Algorithms and Data Structures](http://madhualgo.blogspot.co.nz/2017/01/350-problems.html)

### Open Source
- [Producing Open Source Software](http://producingoss.com/)
- [Open Source Guides](https://opensource.guide/)

### Serverless
-[Serverless on Kubernetes with Soam Vasani](https://softwareengineeringdaily.com/2017/06/12/serverless-on-kubernetes-with-soam-vasani/)

### Management
- [What to do when your startup needs program management](https://blog.intercom.com/what-to-do-when-your-startup-needs-program-management/)

### Incredible Products/Sites
<!-- - [Intelligent Travel Platform of Kuaidi & Didi Group](http://v.kuaidadi.com/) -->
- [Hadoop Weekly](https://www.hadoopweekly.com/)
- [The Morning Paper](https://blog.acolyer.org/)
- [The Wild Week in AI](http://www.wildml.com/newsletter/)
- [Software Engineering Daily](https://softwareengineeringdaily.com/)
- [freeCodeCamp](https://medium.freecodecamp.com/)

### Other Materials
- [All the Apache Streaming Projects: An Exploratory Guide](http://thenewstack.io/apache-streaming-projects-exploratory-guide/)
- [Disrupting Big Data with Apache Spark in the Cloud](https://youtu.be/4uw_obRH5eM)
- [HTTP Made Really Easy](http://www.jmarshall.com/easy/http/)
- [Deep Learning Trends @ ICLR 2016](http://www.computervisionblog.com/2016/06/deep-learning-trends-iclr-2016.html?m=1)
- [Our 500+ engineers all use this front end development guide](https://medium.freecodecamp.com/grabs-front-end-guide-for-large-teams-484d4033cc41)
