# Subtask: Theory

## Purpose
Understand the three pillars of observability.

## Task Details & Parameters
Research Metrics, Logs, and Tracing.

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. Define the three pillars of observability: Metrics, Logs, and Traces.
2. Explain the difference between monitoring a system and making a system observable.
3. How does a pull-based metrics system (like Prometheus) differ from a push-based system?
4. What is a PromQL query, and how are labels used to filter metrics?
5. Describe the architecture of a typical log aggregation stack (e.g., FluentBit/Promtail -> ElasticSearch/Loki).
6. What is the difference between structured logging (JSON) and unstructured logging, and why is structured logging preferred?
7. Explain the purpose of node exporters and kube-state-metrics.
8. What is cardinality in metrics, and why can high cardinality cause performance issues in Prometheus?
9. How does Alertmanager group, inhibit, and route alerts?
10. What is the difference between an alert and an event?
11. How do you monitor the health of Prometheus itself?
12. Describe the RED method (Rate, Errors, Duration) for monitoring services.
13. What is the difference between a gauge, a counter, and a histogram in Prometheus?
14. Explain the concept of log rotation and why it is necessary at the node level.
15. How does the Prometheus `ServiceMonitor` Custom Resource automate metric scraping?
16. What are recording rules in Prometheus, and when should you use them?
17. Describe the pushgateway and state scenarios where it is required.
18. How does a log aggregator parse and extract fields from raw application logs?
19. What is the difference between active monitoring (synthetic tests) and passive monitoring?
20. How can you use Grafana variables to create dynamic and reusable dashboards?