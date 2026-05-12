# Subtask: Theory

## Purpose
Understand the fundamentals of microservices, containers, and Kubernetes concepts.

## Task Details & Parameters
Research Docker, containerization principles, and basic Kubernetes resources (Pods, Deployments, Services, ConfigMaps, etc.).

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. What is the difference between a virtual machine and a container?
2. What are Docker namespaces and cgroups, and how do they isolate containers?
3. Why is it recommended to use multi-stage builds in Docker?
4. What is the purpose of the `.dockerignore` file?
5. Explain the difference between `CMD` and `ENTRYPOINT` in a Dockerfile.
6. What is a Kubernetes Pod and why is it the smallest deployable unit instead of a single container?
7. How does a Kubernetes Deployment differ from a ReplicaSet?
8. Explain the differences between ClusterIP, NodePort, and LoadBalancer service types in Kubernetes.
9. What is the role of the kube-proxy component?
10. How does an Ingress controller route external HTTP/HTTPS traffic to internal services?
11. What is the difference between readiness and liveness probes?
12. Why should the backend and database components be decoupled into separate Pods?
13. What is a ConfigMap, and what are the different ways it can be consumed by a Pod?
14. Explain the concept of a StatefulSet and when you would use it instead of a Deployment.
15. What is an init container, and what are some common use cases for it?
16. How does Kubernetes handle container logs by default, and why is log aggregation necessary?
17. What is a DaemonSet, and give an example of a workload that would use it.
18. Explain the difference between `docker run` and `docker exec`.
19. What is a container registry, and what is the difference between a public and private registry?
20. Why is it considered a bad practice to store state (like database data or uploaded files) within a container's writable layer?
21. What is the difference between a ReplicaSet and a ReplicationController?
22. How do Kubernetes resource requests and limits affect CPU throttling and OOMKills?
23. Describe the function of the Kubernetes Scheduler.
24. What are Kubernetes labels and selectors used for?
25. Explain the concept of a namespace in Kubernetes. Does it provide network isolation by default?
26. What is a Headless Service, and when would you use it?
27. How does the `kubectl port-forward` command work under the hood?
28. Describe the use case for a Kubernetes Job vs. a CronJob.
29. What is a container image layer, and why is the order of instructions in a Dockerfile important?
30. Explain the role of the Container Runtime Interface (CRI) in Kubernetes.