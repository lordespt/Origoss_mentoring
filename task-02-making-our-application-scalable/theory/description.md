# Subtask: Theory

## Purpose
Understand Kubernetes scaling mechanisms.

## Task Details & Parameters
Research Horizontal Pod Autoscaler (HPA), Vertical Pod Autoscaler (VPA), and the Kubernetes Metrics Server.

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. Explain the difference between Horizontal Scaling (scaling out) and Vertical Scaling (scaling up).
2. How does the Horizontal Pod Autoscaler (HPA) calculate when to scale up or down based on CPU utilization?
3. What is the role of the Kubernetes Metrics Server in autoscaling?
4. What happens if a Pod does not have resource requests defined, and an HPA is configured for CPU utilization?
5. How does the Vertical Pod Autoscaler (VPA) adjust resource limits and requests?
6. Explain the difference between VPA's `Off`, `Initial`, `Recreate`, and `Auto` modes.
7. Can HPA and VPA be used together on the same target metric? If not, why?
8. What is the difference between custom metrics and external metrics in the context of HPA?
9. How does cluster autoscaling differ from pod autoscaling?
10. Describe a scenario where vertical scaling is preferred over horizontal scaling.
11. What is scaling thrashing (or flapping), and how does HPA mitigate it?
12. How do resource limits and requests affect pod scheduling?
13. How does the cluster autoscaler decide when to add or remove nodes?
14. What are the limitations of scaling stateful applications compared to stateless ones?
15. Explain how readiness probes interact with HPA during a scale-up event.
16. What is the difference between CPU utilization percentage and absolute CPU usage in HPA metrics?
17. Can HPA scale deployments based on memory usage? If so, what are the challenges compared to CPU?
18. How do custom metrics providers like Prometheus Adapter integrate with the Kubernetes metrics API?
19. What is the cooldown period in HPA, and why is it important for stabilization?
20. Explain the difference between `minReplicas` and `maxReplicas` and how they constrain HPA behavior.