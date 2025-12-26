# Plugin Architecture (Extensible Architecture)

This project demonstrates an extensible architecture using dynamically loaded plugins.

## Structure
- **src/Core**: Central application logic and abstraction layer.
- **src/Plugins**: Example plugins (`EmailPlugin`, `PaymentPlugin`, `ReportingPlugin`).
- **src/Shared**: Common configuration and utility models.

## Key Principles
- **Open-Closed Principle**: The core is closed for modification but open for extension.
- **Dynamic Loading**: Plugins are discovered and loaded at runtime from a specific directory.
- **Strict Isolation**: Plugins cannot talk to each other directly; they only interact with the Core.
