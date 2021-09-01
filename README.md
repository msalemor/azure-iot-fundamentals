# azure-iot-learn
Azure IoT Fundamentals

## Devices

## Protocols

- MQTT
- MQTT over WebSockets
- AMQP
- AMQP over WebSockets
- HTTPS

Use on all devices that do not require to connect multiple devices (each with its own per-device credentials) over the same TLS connection.
- MQTT: 
- MQTT over WebSockets

Use on field and cloud gateways to take advantage of connection multiplexing across devices.
- AMQP
- AMQP over WebSockets

Use for devices that cannot support other protocols.
- HTTPS

Protocol	When you should choose this protocol
MQTT
MQTT over WebSocket	Use on all devices that do not require to connect multiple devices (each with its own per-device credentials) over the same TLS connection.
AMQP
AMQP over WebSocket	Use on field and cloud gateways to take advantage of connection multiplexing across devices.
HTTPS	Use for devices that cannot support other protocols.

## IoT Hub

### Networking
### Scaling
### Device Registration
#### Certificates

## Digital Twin

- A json representation of the device that can be used to read and set (desired state) properties to and from the device.
