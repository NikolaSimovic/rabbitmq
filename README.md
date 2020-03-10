# SpringBoot + RabbitMQ

This is a simple SpringBoot app that implements the RabbitMQ messaging broker, and works at the same time as bot, the Producer and Reciever.

## Requirements
You need to have RabbitMQ runnining locally in order make this work. The easiest way is to use Docker:

```
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management
```
