# Azure IoT Fundamentals

## Architecture

- Devices
- Cloud Gateway
- Device Provisions
- Stream Processing
- ML
- Warm Storage
- Cold Storage
- Data Transformation
- Business process integration

## Devices

### Physcal tamper-proof
- TPM
- Secure boot
- Intrusion detection and "digital self-destruction"

### DPS (Deive Provisioning Service)
- Provisioning at sscale

### Phone as an IoT Device

- [Your phone as an IoT device](https://docs.microsoft.com/en-us/azure/iot-fundamentals/iot-phone-app-how-to)

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

- Public
- Filtered (Open/Reject IP ranges)
- Private Endpoint

### Scaling
### Device Registration
#### Certificates
### IoT Explorer

- [Graphical tool for interactive with devices connected to IoT hub](https://docs.microsoft.com/en-us/azure/iot-fundamentals/howto-use-iot-explorer)

## Digital Twin

- A json representation of the device that can be used to read and set (desired state) properties to and from the device.


## Development
