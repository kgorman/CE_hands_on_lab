# Configure Sink

A sink is a defined as a logical table that can reference a kafka topic, a database connection or other destination for data after the processing is complete. The sink schema must match the output defintion (names/types) of the stream processing query.

- Use a local Kafka topic
- Auto-generate schema definition using templates dropdown.

[Example](../examples/create_sink.sql)

[Documentation](https://docs.cloudera.com/csa-ce/1.6.0/getting-started/topics/csa-ce-add-sink.html)
