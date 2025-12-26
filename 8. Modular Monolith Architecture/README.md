# Modular Monolith Architecture

This project demonstrates a Modular Monolith, balancing the benefits of microservices with the simplicity of a single deployment.

## Structure
- **src/Modules**: Independent business modules (Orders, Catalog, Customers).
- **src/Shared**: Common abstractions and infrastructure.
- **src/Bootstrapper**: The core host that initializes and runs all modules.

## Key Principles
- **Modular Autonomy**: Each module is self-contained and isolated.
- **Tight Boundaries**: Modules communicate through shared interfaces or event buses.
- **Unified Deployment**: All modules are hosted and deployed together as a single unit.
