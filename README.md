# Examples

### TODO
stringsvc is a tutorial that takes you through writing a service from first principles. It can help you understand the decisions that went into Go kit’s design.

addsvc is the original example service. It exposes a set of operations over all supported transports. It’s fully logged, instrumented, and uses distributed tracing. It also demonstrates how to create and use client packages. It demonstrates almost all of Go kit’s features.

profilesvc demonstrates how to use Go kit to write a microservice with a REST-ish API. It uses net/http and the excellent Gorilla web toolkit.

shipping is a complete, “real-world” application composed of multiple microservices, based on Domain Driven Design principles.

apigateway demonstrates how to implement the API gateway pattern backed by a Consul service discovery system.
