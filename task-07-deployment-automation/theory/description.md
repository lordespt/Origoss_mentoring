# Subtask: Theory

## Purpose
Understand continuous delivery and cluster bootstrapping.

## Task Details & Parameters
Research GitOps principles, declarative infrastructure, and CI/CD pipelines.

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. What is GitOps, and what are its core principles?
2. Contrast the "Push" deployment model (e.g., standard Jenkins pipeline) with the "Pull" model (e.g., ArgoCD).
3. Why is Git considered the "single source of truth" in a GitOps workflow?
4. How does ArgoCD detect configuration drift in a Kubernetes cluster?
5. What are the benefits of separating application source code from infrastructure/deployment manifests into different repositories?
6. Explain the concept of declarative infrastructure.
7. What are the challenges of managing secrets in a GitOps workflow, and how can they be addressed?
8. How does an ArgoCD Application resource map a Git repository to a Kubernetes namespace?
9. Explain the App of Apps pattern in ArgoCD.
10. What is continuous validation, and why should manifests be linted and tested in CI before being merged?
11. How do you handle environment promotion (e.g., Dev -> Staging -> Prod) in GitOps?
12. What happens if someone manually edits a Kubernetes Deployment that is managed by ArgoCD?
13. What is the difference between imperative and declarative infrastructure management?
14. Explain the role of Kustomize vs. Helm in a GitOps workflow.
15. How does ArgoCD handle secrets management if secrets cannot be stored in plaintext in Git?
16. What is the purpose of ArgoCD Sync Hooks and how can they be used in a deployment pipeline?
17. Describe the differences between ArgoCD and FluxCD.
18. How do you implement progressive delivery (Canary/Blue-Green) with GitOps?
19. What is a monorepo vs. polyrepo approach in GitOps, and what are the pros/cons?
20. How can you ensure that a misconfigured Git commit doesn't break the entire cluster via GitOps?