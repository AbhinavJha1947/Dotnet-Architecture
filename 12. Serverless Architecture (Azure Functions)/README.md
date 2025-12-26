# Serverless Architecture (Azure Functions)

This project demonstrates a serverless approach using Azure Functions for various triggers.

## Structure
- **src/Functions**: Function apps for HTTP, Queue, and Timer triggers.
- **src/Functions/OrchestrationFunctions**: Durable Functions for long-running workflows.
- **src/Shared**: Domain logic and services shared across function apps.

## Key Principles
- **Event-Driven Execution**: Functions run in response to specific system events.
- **Scalability**: Each function can scale independently based on demand.
- **Statelessness**: Logic is designed to be stateless and short-lived.
