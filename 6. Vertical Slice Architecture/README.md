# Vertical Slice Architecture

This project implements Vertical Slice Architecture, organizing code by functional features rather than technical layers.

## Structure
- **src/WebApi**: Contains all features as independent slices.
  - **Features/Orders**: Everything related to orders (Commands, Queries, Controllers, Entities).
  - **Features/Products**: Everything related to products.
- **tests/Features.Orders.Tests**: Unit tests for the specific feature slice.

## Key Principles
- **Feature Encapsulation**: Each feature contains everything it needs.
- **Reduced Coupling**: Changing one feature doesn't affect others.
- **Simplicity**: Avoids the "spaghetti" of layers by keeping related code together.
