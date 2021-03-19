Create a new topic.

`./kafka/bin/kafka-topics.sh --bootstrap-server localhost:9092 --topic test --create --partitions 1`{{execute}}

List the topics.

`./kafka/bin/kafka-topics.sh --bootstrap-server localhost:9092 --list`{{execute}}

Produce a record. Enter the following command, and then enter some text at the `>` prompt using `Enter` to produce the record.  When you're done, using `Ctrl-d` to close the producer.

`./kafka/bin/kafka-console-producer.sh --broker-list localhost:9092 --topic test`
