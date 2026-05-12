# Subtask: Theory

## Purpose
Understand distributed tracing and application profiling.

## Task Details & Parameters
Research OpenTelemetry, Jaeger, Tempo, and continuous profiling tools like Pyroscope.

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. What is Distributed Tracing, and what specific problem does it solve in microservice architectures?
2. Define "Trace" and "Span" in the context of distributed tracing.
3. How is trace context (Trace ID, Span ID) propagated between different microservices over HTTP?
4. What is OpenTelemetry (OTel), and why is it important as a standard?
5. Explain the role of the OpenTelemetry Collector.
6. What is the difference between auto-instrumentation and manual instrumentation?
7. How does sampling work in distributed tracing, and why is it necessary for high-throughput systems?
8. Contrast Head-based sampling with Tail-based sampling.
9. What is continuous application profiling, and what kind of insights does it provide?
10. Explain how to read a Flame Graph. What do the x-axis and y-axis represent?
11. How does profiling differ from tracing in identifying performance bottlenecks?
12. What are the overhead implications of running continuous profiling in production environments?
13. How does OpenTelemetry differ from vendor-specific tracing SDKs (like Jaeger or Datadog)?
14. Describe the concept of Baggage in OpenTelemetry context propagation.
15. What is the W3C Trace Context standard?
16. How can you correlate a specific log line with a distributed trace?
17. Explain the differences between CPU profiling, Memory profiling, and Mutex profiling.
18. What is the purpose of an eBPF-based profiler, and how does it compare to language-specific profilers (like pprof)?
19. How does tracing help in identifying the root cause of a high-latency API response involving multiple microservices?
20. What is an Exemplar in the context of distributed tracing, and how does it differ from Baggage?