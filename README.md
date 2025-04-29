# Homematic IP Connect API Overview

The Homematic IP Connect API enables developers to create plugins that integrate seamlessly with the Homematic IP ecosystem. By leveraging this API, developers can extend the functionality of the Homematic IP Home Control Unit (HCU) to include third-party devices, custom control, and advanced monitoring capabilities.

## Key Features

- **Plugin Integration**: Build plugins to control, monitor, and extend the Homematic IP system.
- **WebSocket Communication**: The API operates over WebSocket, providing real-time communication between plugins and the HCU.
- **Extensibility**: Add support for third-party devices, create custom handling, and enhance user interactions.
- **Documentation and Examples**: Comprehensive documentation and example implementations are available to help developers get started quickly.

## Repository Structure

This organization hosts several repositories to support the development and integration of plugins:

- **[connect-api](https://github.com/homematicip/connect-api)**: The core repository containing the Homematic IP Connect API, including example plugins for Java and Node.js.
- **[connect-api-java](https://github.com/homematicip/connect-api-java)**: A Java-based implementation of the Connect API for plugin development.
- **[connect-api-documentation-model](https://github.com/homematicip/connect-api-documentation-model)**: A library for defining metadata and annotations for the Java-based implementation

## Getting Started

1. **Explore the API**: Begin by reviewing the [connect-api](https://github.com/homematicip/connect-api) repository, which contains the core API and example implementations.
2. **Develop Plugins**: Use the provided examples and libraries to create your own plugins for the Homematic IP system.
3. **Test and Deploy**: Test your plugins locally or in a containerized environment before deploying them to the HCU.

## License

All connect-api repositories in this organization are licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt).

## Maintainer

Developed and maintained by **eQ-3 AG**.\
Homematic IP is a trademark of **eQ-3 AG**.

