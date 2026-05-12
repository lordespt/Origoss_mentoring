# Subtask: Theory

## Purpose
Understand the challenges and solutions for managing secrets in Kubernetes.

## Task Details & Parameters
Research Kubernetes native secrets, their limitations (base64 encoding), and external secret management tools.

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. How are native Kubernetes Secrets stored in etcd by default?
2. Why is base64 encoding not considered encryption?
3. What is the purpose of "Encryption at Rest" in Kubernetes, and does it solve the secret distribution problem?
4. Explain the "Secret Zero" problem in secret management.
5. How does HashiCorp Vault integrate with Kubernetes to provide secrets to Pods?
6. What is the difference between injecting a secret as an environment variable vs. a volume mount?
7. Explain the concept of dynamic secrets and their benefits over static credentials.
8. How does the Sealed Secrets controller work, and what problem does it solve in a GitOps workflow?
9. Describe the Kubernetes Auth Method in Vault and how it utilizes Service Account Tokens.
10. What are the security risks of storing secrets in a Git repository even if it is private?
11. How do you rotate a compromised secret in a live Kubernetes cluster?
12. Explain the role of the External Secrets Operator (ESO) and how it differs from Vault Agent.
13. Describe the Transit Secrets Engine in Vault and its use cases.
14. How does the Secret Provider Class map external secrets to Kubernetes native secrets using the CSI Secret Store?
15. What are the potential security risks of using the `envFrom` field with a Secret?
16. Explain how Kubernetes Role-Based Access Control (RBAC) is used to restrict access to Secrets.
17. What is Vault Agent Injector, and how does it use annotations to render secrets?
18. How does OpenBao differ from HashiCorp Vault?
19. Why is auditing and logging of secret access critical in a production environment?
20. Explain how asymmetric cryptography is utilized by the Sealed Secrets controller.