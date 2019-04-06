# RabbitMQ
RabbitMQ 学习笔记

初识RabbitMQ：RanbbitMQ是一个开源的消息代理和队列服务器，用来通过普通协议在完全不同的应用之间共享数据，RabbitMQ是使用Erlang语言来编写的，并且RabbitMQ是基于AMQP协议的

优点：  开源，性能优秀，稳定性保障 
       提供可靠性消息投递模式（confirm），返回模式（return）
       与SpringAMQP完美的整合，API丰富
       集群模式丰富，表达式配置，HA模式，镜像队列模式
       保证数据不丢失的前提做到高可靠性，可用性
       
RabbitMQ高性能原因：
      Erlang语言最初在于交换机领域的架构模式，这样使得RabbitMQ在Broker 之间进行数据交互的性能是非常优秀的
      Eralang的优点：有着和原生Socket一样的延迟
