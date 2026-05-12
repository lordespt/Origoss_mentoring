# Subtask: Theory

## Purpose
Understand OpenID Connect (OIDC) and OAuth2.

## Task Details & Parameters
Research OIDC flows, JWT tokens, and how identity providers integrate with applications.

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. What is the difference between Authentication (AuthN) and Authorization (AuthZ)?
2. Explain the relationship between OAuth 2.0 and OpenID Connect (OIDC).
3. What is a JSON Web Token (JWT), and what are its three main parts?
4. Describe the OIDC Authorization Code flow step-by-step.
5. What is the role of an Identity Provider (IdP) in OIDC?
6. Explain the difference between an ID Token and an Access Token.
7. What is a Client ID and a Client Secret in the context of OIDC?
8. How can you secure a Kubernetes-hosted application using an authenticating proxy (like OAuth2-Proxy)?
9. What is the purpose of the OIDC Discovery endpoint (`/.well-known/openid-configuration`)?
10. How does Kubernetes use OIDC for API server authentication?
11. What are OIDC scopes and claims? Provide examples.
12. Why is it dangerous to implement your own authentication logic instead of using OIDC/SAML?
13. What is the purpose of the UserInfo endpoint in OIDC?
14. Describe the Implicit Flow and why it is no longer recommended for modern applications.
15. How does Proof Key for Code Exchange (PKCE) enhance the security of the Authorization Code flow?
16. What is the difference between a Confidential Client and a Public Client?
17. Explain the concept of a Refresh Token and how it is securely used.
18. How does Dex act as an identity broker for Kubernetes?
19. Describe the process of configuring `kube-apiserver` to use OIDC for authentication.
20. What is RBAC mapping, and how do OIDC claims map to Kubernetes Groups and Users?