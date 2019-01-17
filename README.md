# Surveil

Surveil is a service that monitors service availability and health in a distributed system. It uses [Magellan](https://github.com/alex-c/Magellan) and therefore [Consul](https://github.com/hashicorp/consul) to aggregate data about available services, service instances and health checks. Surveil provides that data through a REST interface, and allows clients to subcribe to that data through WebSockets.

The Surveil website (name TBD) allows to live monitor the data provided by Surveil.

## Status

Surveil is in early development.
