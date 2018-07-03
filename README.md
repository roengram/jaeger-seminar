# Jaeger

## Demo

- HotRod
  - [Blog](https://medium.com/opentracing/take-opentracing-for-a-hotrod-ride-f6e3141f7941)
  - [GitHub](https://github.com/jaegertracing/jaeger/tree/master/examples/hotrod)

## OpenTracing

- [Specification](https://github.com/opentracing/specification/blob/master/specification.md)
  - Trace, span
  - References between spans
  - Tag and Log: [convention](https://github.com/opentracing/specification/blob/master/semantic_conventions.md)
  - Baggage
  - Carrier
  - Case of Golang
- Implementations
  - Jaeger
  - Appdash
  - LightStep
  - Hawkular

## Jaeger

- [Architecture](https://www.jaegertracing.io/docs/architecture/)

## Tutorial

- https://github.com/yurishkuro/opentracing-tutorial
  - One depth tracing. Tags and Logs
  - In-process tracing. [Context in Golang](https://medium.com/@cep21/how-to-correctly-use-context-context-in-go-1-7-8f2c0fafdf39)
  - Distributed tracing
  - Baggage

- HotRod
  - Microservices dependency architecture
  - Error highlighted - semantic convention
  - Contextualized logging
  - Identifying source of latency
  - Resource usage attribution via baggage
  - Instrumentation
    - [HTTP](https://github.com/jaegertracing/jaeger/blob/d4abb8933a501138ba9e90e87b16d08bebfea975/examples/hotrod/services/frontend/server.go#L58)
    - [TChannel](https://github.com/jaegertracing/jaeger/blob/33a167bb87511e67c7584a3dcd8112b06a21724d/examples/hotrod/services/driver/server.go#L39)
    - [Redis simulation](https://github.com/jaegertracing/jaeger/blob/33a167bb87511e67c7584a3dcd8112b06a21724d/examples/hotrod/services/driver/redis.go#L50)
    - [gRPC](https://github.com/grpc-ecosystem/grpc-opentracing)
  - Metrics on RPC endpoints
