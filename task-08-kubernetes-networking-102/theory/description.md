# Subtask: Theory

## Purpose
Understand advanced traffic management.

## Task Details & Parameters
Research standard Ingress vs. Gateway API, load balancing algorithms, and the purpose of a Service Mesh.

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. How does a standard Kubernetes Ingress resource differ from the Gateway API?
2. What were the main limitations of the Ingress API that led to the creation of the Gateway API?
3. Explain the roles of GatewayClass, Gateway, and HTTPRoute in the Gateway API.
4. How does a bare-metal cluster expose LoadBalancer services without a cloud provider (e.g., using MetalLB)?
5. Explain the difference between Layer 4 (Transport) and Layer 7 (Application) load balancing.
6. What is a Service Mesh, and what primary problems does it solve?
7. Describe the sidecar proxy pattern used by service meshes like Istio.
8. How does an eBPF-based service mesh differ from a sidecar-based one in terms of architecture and performance?
9. What is mutual TLS (mTLS), and how does a service mesh automate it?
10. How does a service mesh handle traffic routing (like canary releases or blue/green deployments)?
11. What is SNI (Server Name Indication) routing?
12. How does CoreDNS resolve internal Kubernetes service names to ClusterIPs?
13. Explain how the Gateway API handles cross-namespace routing.
14. What is the difference between a Gateway and a GatewayClass?
15. Describe how a LoadBalancer service type allocates an IP address in a bare-metal environment vs. a cloud environment.
16. What is the role of an Ingress Controller's admission webhook?
17. Explain the concept of traffic splitting and weight-based routing in the Gateway API.
18. How does a Service Mesh implement distributed tracing for network calls?
19. What are the performance implications of adding a sidecar proxy to every pod in a cluster?
20. Describe how Cilium uses eBPF to bypass the standard iptables network stack in Kubernetes.