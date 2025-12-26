# Event-Driven Architecture (EDA)

This project focuses on asynchronous communication between decoupled services using an Event Bus.

## Structure
- **src/Services**: Services acting as producers and consumers of events.
- **src/BuildingBlocks/EventBus**: Abstractions for RabbitMQ and Azure Service Bus.
- **src/BuildingBlocks/Common**: Shared integration event base classes.

## Key Principles
- **Asynchronous Communication**: Services don't wait for responses from other services.
- **Decoupling**: Services only know about the event schema, not who produces or consumes it.
- **Reliability**: Uses patterns like the Outbox pattern to ensure event delivery.
