# Kafka docker-compose Setups

This repositories contains *docker-compose* setup files (`docker-compose.yml`, *JAAS* files, Property files)  for Confluent Kafka containers (Zookeeper, Kafka broker, Control-Center) with different security settings:

- without security - see [kafka-insecure](./kafka-insecure)
- SASL_PLAIN on broker and SASL on zookeeper - see [kafka-sasl-plain](./kafka-sasl-plain)
- SASL_SCRAM on broker and SASL on zookeeper  - see [kafka-sasl-scram](./kafka-sasl-scram)

## Links

- [Confluent Docs - Authentication with SASL](https://docs.confluent.io/current/kafka/authentication_sasl/index.html)
- [Confluent Docs - Configuring SCRAM](https://docs.confluent.io/current/kafka/authentication_sasl/authentication_sasl_scram.html)
