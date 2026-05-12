# Subtask: Theory

## Purpose
Understand Kubernetes security contexts and cluster-level security policies.

## Task Details & Parameters
Research Pod Security Contexts, container capabilities, and Policy-as-Code engines (e.g., Kyverno, OPA Gatekeeper).

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. What is the Principle of Least Privilege, and how does it apply to Kubernetes workloads?
2. Explain the difference between running a container as root vs. non-root. What are the risks of the former?
3. What is a Pod Security Context, and what kind of settings can be configured within it?
4. What are Linux Capabilities, and why is it recommended to drop `ALL` capabilities and only add back the required ones?
5. How does a read-only root filesystem improve the security of a container?
6. What is `allowPrivilegeEscalation` and why should it generally be set to `false`?
7. Describe what seccomp profiles are and how they restrict container behavior.
8. What is a Pod Security Admission (PSA) controller, and how does it replace PodSecurityPolicies (PSP)?
9. Explain the difference between the `Privileged`, `Baseline`, and `Restricted` Pod Security Standards.
10. What is Policy-as-Code, and what benefits does it bring to cluster administration?
11. Compare OPA Gatekeeper and Kyverno. What are their core architectural differences?
12. What is a mutating admission webhook, and how can it be used for security?
13. How does RBAC (Role-Based Access Control) differ from Pod Security?
14. What is the purpose of the `runAsNonRoot` and `runAsUser` directives?
15. How does NetworkPolicy restrict traffic between pods in a Kubernetes cluster?
16. What is the difference between ingress and egress rules in a NetworkPolicy?
17. Explain how a Service Mesh can enhance cluster security beyond NetworkPolicies.
18. Describe what the Kubernetes Audit Logs record and why they are important for security.
19. What are Admission Controllers, and what role do they play in Policy-as-Code?
20. How do you securely manage container images, and what is image signing/scanning?