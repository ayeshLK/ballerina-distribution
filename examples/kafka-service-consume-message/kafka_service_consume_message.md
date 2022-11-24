# Kafka service - Consume message

Here, a Kafka consumer is used as a listener to a service with automatic offset commits. For this to work properly, an active Kafka broker should be present.

::: code kafka_service_consume_message.bal :::

::: out kafka_service_consume_message.out :::

## Related links
- [`kafka:Listener` - API documentation](https://lib.ballerina.io/ballerinax/kafka/3.4.0/clients/Listener)
- [Service usage - specification](https://github.com/ballerina-platform/module-ballerinax-kafka/blob/master/docs/spec/spec.md#432-usage)