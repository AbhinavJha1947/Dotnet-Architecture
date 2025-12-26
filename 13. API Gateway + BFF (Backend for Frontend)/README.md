# API Gateway + BFF (Backend for Frontend)

This project demonstrates optimized client communication using specialized Backend for Frontend layers.

## Structure
- **src/Gateways/ApiGateway**: Central routing and cross-cutting concern entry.
- **src/Gateways/WebBFF**: Aggregator tailored for Web clients.
- **src/Gateways/MobileBFF**: Aggregator tailored for Mobile clients.
- **src/Services**: Core backend microservices.

## Key Principles
- **Aggregation**: BFFs merge data from multiple services to reduce client round-trips.
- **Tailored APIs**: Each client type gets exactly the data it needs in the optimal format.
- **Simplified Client Logic**: Moves data transformation and aggregation from the client to the server.
