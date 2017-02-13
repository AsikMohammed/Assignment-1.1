ASSIGNMENT 1
1) VARIOUS SOURCES OF BIGDATA:
        1) Documents: PDF,PPT,Plain Text,HTML,XML etc,.
        2) Media: Images,Videos,Live Streams, Podcasts etc,.
        3) Archives: Archives of scanned documents, Insurance forms,medical records etc,.
        4) Data Storage: SQL,Hadoop,NoSQL,file systems
        5) Social Media
        6) Public Web
        7) Sensor Data
2) 3Vs OF BIG DATA:
        1)Volume
        2)Variety
        3)Velocity
3) HORIZONTAL  SCALING AND VERTICAL SCALING:
         Horizontal Scaling: In a database world horizontal-scaling is often based on partitioning of the data i.e. each node contains only part of the data, Horizontal scaling means that you scale by adding more machines into your pool of resources.
         Vertical Scaling: Vertical scaling means that you scale by adding more power (CPU, RAM) to an existing machine.Vertical-scaling the data resides on a single node and scaling is done through multi-core i.e. spreading the load between the CPU and RAM resources of that machine.
4) NEED AND WORKING OF HADOOP:
        Need of Hadoop: Basically, it’s a way of storing enormous data sets across distributed clusters of servers and then running “distributed” analysis applications in each cluster.It’s designed to be robust, in that your Big Data applications will continue to run even when individual servers — or clusters — fail. And it’s also designed to be efficient, because it doesn’t require your applications to shuttle huge volumes of data across your network.
        Working of Hadoop: It has two main parts – a data processing framework and a distributed filesystem for data storage. The Hadoop Distributed File System (HDFS) is designed to store very large data sets reliably, and to stream those data sets at high bandwidth to user applications. In a large cluster, thousands of servers both host directly attached storage and execute user application tasks. By distributing storage and computation across many servers, the resource can grow with demand while remaining economical at every size. 
        Hadoop MapReduce is a software framework for easily writing applications which process vast amounts of data (multi-terabyte data-sets) in-parallel on large clusters (thousands of nodes) of commodity hardware in a reliable, fault-tolerant manner.A MapReduce job usually splits the input data-set into independent chunks which are processed by the map tasks in a completely parallel manner.
