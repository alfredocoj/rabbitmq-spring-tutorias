## Official RabbitMQ Tutorials for SpringBoot

Tutorials:
- Hello World (Tutorial 1)
- Work queues (Tutorial 2)
- Publish / Subscribe with Fanout Exchange - (Tutorial 3)


SEND
```
mvn clean package

java -jar target/rabbitmq-amqp-1.0-SNAPSHOT.jar --spring.profiles.active=work-queues,sender
java -jar target/rabbitmq-amqp-1.0-SNAPSHOT.jar --spring.profiles.active=work-queues,receiver

java -jar target/rabbitmq-amqp-1.0-SNAPSHOT.jar --spring.profiles.active=pub-sub,sender --tutorial.client.duration=60000
java -jar target/rabbitmq-amqp-1.0-SNAPSHOT.jar --spring.profiles.active=pub-sub,receiver --tutorial.client.duration=60000



```

## References

[Tutorial 1](https://www.rabbitmq.com/tutorials/tutorial-one-spring-amqp.html)

[Tutorial 2](https://www.rabbitmq.com/tutorials/tutorial-two-spring-amqp.html)

[Tutorial 3](https://www.rabbitmq.com/tutorials/tutorial-three-spring-amqp.html)

[Getting Started](https://www.rabbitmq.com/getstarted.html)

[AMQP Conceitos](https://www.rabbitmq.com/tutorials/amqp-concepts.html)

[Tutoriais AMQP em C++](https://github.com/RPG-18/rabbitmq-cpp-tutorials)
