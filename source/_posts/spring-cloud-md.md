---
title: spring-cloud.md
date: 2016-11-11 15:12:31
tags: [微服务]
---

## Spring Cloud Config
Centralized external configuration management backed by a git repository. The configuration resources map directly to Spring `Environment` but could be used by non-Spring applications if desired.
基于git仓库的集中式外部配置管理。配置资源将被直接映射到spring环境变量中，如果有必要也可以在非spring环境中使用。

## Spring Cloud Netflix
Integration with various Netflix OSS components (Eureka, Hystrix, Zuul, Archaius, etc.).
集成了Netflix OSS(open source software)开源组件，便于和spring集成构建微服务。

## Spring Cloud Bus
An event bus for linking services and service instances together with distributed messaging. Useful for propagating state changes across a cluster (e.g. config change events).
一个使用分布式消息构建的，用来链接不同的服务或者同一类的服务不同实例的事件总线。能够用于跨集群传播状态变化。

## Spring Cloud for Cloud Foundry
Integrates your application with Pivotal Cloudfoundry. Provides a service discovery implementation and also makes it easy to implement SSO and OAuth2 protected resources, and also to create a Cloudfoundry service broker.
Pivotal Cloudfoundry是一个国外的PaaS平台提供商，这个子项目方便你在Pivotal Cloudfoundry平台上集成你的应用。提供了服务发现的实现，并且更易于在CloudFoundry平台上实现单点登录和OAuth2，以及更易于创建Cloudfoundry的服务Broker。

## Spring Cloud Cloud Foundry Service Broker
Provides a starting point for building a service broker that manages a Cloud Foundry managed service.

## Spring Cloud Cluster
Leadership election and common stateful patterns with an abstraction and implementation for Zookeeper, Redis, Hazelcast, Consul.
选主

## Spring Cloud Consul
Service discovery and configuration management with Hashicorp Consul.

## Spring Cloud Security
Provides support for load-balanced OAuth2 rest client and authentication header relays in a Zuul proxy.

## Spring Cloud Sleuth
Distributed tracing for Spring Cloud applications, compatible with Zipkin, HTrace and log-based (e.g. ELK) tracing.

## Spring Cloud Data Flow
A cloud-native orchestration service for composable microservice applications on modern runtimes. Easy-to-use DSL, drag-and-drop GUI, and REST-APIs together simplifies the overall orchestration of microservice based data pipelines.

## Spring Cloud Stream
A lightweight event-driven microservices framework to quickly build applications that can connect to external systems. Simple declarative model to send and receive messages using Apache Kafka or RabbitMQ between Spring Boot apps.

## Spring Cloud Stream App Starters
Spring Cloud Stream App Starters are Spring Boot based Spring Integration applications that provide integration with external systems.

## Spring Cloud Task
A short-lived microservices framework to quickly build applications that perform finite amounts of data processing. Simple declarative for adding both functional and non-functional features to Spring Boot apps.

## Spring Cloud Task App Starters
Spring Cloud Task App Starters are Spring Boot applications that may be any process including Spring Batch jobs that do not run forever, and they end/stop after a finite period of data processing.

## Spring Cloud Zookeeper
Service discovery and configuration management with Apache Zookeeper.

## Spring Cloud for Amazon Web Services
Easy integration with hosted Amazon Web Services. It offers a convenient way to interact with AWS provided services using well-known Spring idioms and APIs, such as the messaging or caching API. Developers can build their application around the hosted services without having to care about infrastructure or maintenance.

## Spring Cloud Connectors
Makes it easy for PaaS applications in a variety of platforms to connect to backend services like databases and message brokers (the project formerly known as "Spring Cloud").

## Spring Cloud Starters
Spring Boot-style starter projects to ease dependency management for consumers of Spring Cloud. (Discontinued as a project and merged with the other projects after Angel.SR2.)

## Spring Cloud CLI
Spring Boot CLI plugin for creating Spring Cloud component applications quickly in Groovy