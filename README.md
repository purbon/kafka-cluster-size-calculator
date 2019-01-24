# A simple Apache Kafka cluster calculator

Have you ever wonder how to size your Apache Kafka cluster, this
spreadsheet will hopefully provide you with some guidance.

In this calculator your will find guidance for:

* Calculating the number of nodes/brokers need.
* Aproximate the numnber of partitions.

The brokers/nodes are calculated based on disk usage but as well on the
network and disk requirements. 

The number of partitions are calculated based on latency and thoughput
optimizations.

I hope this helps.

-- Pere
