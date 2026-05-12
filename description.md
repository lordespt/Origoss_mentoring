# Mentoring Tasks Overview

# Mentoring task 1: Dockerizing and Exposing a simple web application

## Purpose
The purpose of this task is to get the mentee familiar with the basics of microservice architectures and exposing services.

The mentee should choose a frontend and backend project from here:
- Frontend
- Backend

## Prerequisites
- Working local Kubernetes

## Acceptance Criteria
- A new Git repository is created in the Origoss organization containing all manifests and theoretical answers.
- A system diagram representing the deployed architecture is created and added to the repository.
- Both the Frontend and Backend are dockerized according to industry best practices.
- The Backend and the Database are decoupled (i.e., not running in the same pod/deployment. Only applicable if the original project has a coupled backend like SQLite).
- The application runs without errors (missing features or documented bugs should not be fixed or implemented).
- The built docker images are pulled from a registry (either local running in the Kubernetes cluster or ECR or something similar).
- Theoretical questions are answered correctly.

---

# Mentoring task 2: Making our application scalable

## Purpose
The purpose of this task is to get the mentee familiar with the autoscaling options offered by Kubernetes (Horizontal and Vertical scaling). KEDA is not in the scope of this task and will be covered in a later mentoring task.

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Absolved Mentoring task 1

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- Working autoscaling solution.
- The Frontend and Backend deployments are separately scalable.
- Answered theoretical questions.

---

# Mentoring task 3: Secret management

## Purpose
The purpose of this task is to get the mentee acclimated with secret management and related tools (Vault, OpenBao, Sealed Secrets, etc.).

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Absolved Mentoring task 1

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- Demonstrated working solution.
- Answered theoretical questions.

---

# Mentoring task 4: Securing our cluster

## Purpose
The purpose of this task is to get the mentee familiar with Kubernetes security practices (e.g., security contexts on a pod level and how to enforce these on a namespace level).

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Absolved Mentoring task 1

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- Demonstrated working solution.
- Solution is compliant with security best practices.
- Answered theoretical questions.

---

# Mentoring task 5: Storage

## Purpose
The purpose of this task is to get the mentee familiar with the storage solutions provided by Kubernetes (ephemeral and persistent storage, storage classes, PVC, PV, PV replication, etc.).

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Absolved Mentoring task 1

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- Demonstrated working solution.
- Answered theoretical questions.

---

# Mentoring task 6: OIDC integration/implementation

## Purpose
The purpose of this task is to get the mentee familiar with OIDC concepts and where it can be implemented in Kubernetes. At the end of this task, the mentee should be familiar with at least 1 OIDC solution (Keycloak, Zitadel, etc.).

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Absolved Mentoring task 1

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- Demonstrated working OIDC solution integrated with an application or the cluster.
- Answered theoretical questions regarding OIDC flows and components.

---

# Mentoring task 7: Deployment automation

## Purpose
The purpose of this task is to get the mentee familiar with the different provisioning solutions to set up Kubernetes clusters and bootstrapping ArgoCD.

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Basic understanding of Git

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- ArgoCD is successfully bootstrapped on the local cluster.
- Applications are deployed using GitOps principles.
- Answered theoretical questions about GitOps and deployment automation.

---

# Mentoring task 8: Kubernetes networking 102

## Purpose
The purpose of this task is to get the mentee acclimated with more advanced Kubernetes networking concepts (Gateway API, load balancers, service meshes).

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Absolved Mentoring task 1

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- Demonstrated working solution involving Gateway API, a load balancer, or a service mesh.
- Answered theoretical questions comparing these advanced networking concepts.

---

# Mentoring task 9: Observability 101

## Purpose
The purpose of this task is to get the mentee familiar with the basics of observability (metrics collection, log aggregation, alerting).

The mentee should engineer a solution inside the previously configured local Kubernetes that satisfies these criteria. The solution can use any observability ecosystem (Grafana, ELK, VictoriaMetrics, etc.).

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Absolved Mentoring task 1

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- Working observability stack (metrics, logs, alerting) is deployed.
- Demonstrated ability to view application metrics and logs.
- Answered theoretical questions about observability pillars.

---

# Mentoring task 10: Observability 102

## Purpose
The purpose of this task is to get the mentee acclimated with more advanced observability aspects (tracing, profiling).

## Prerequisites
- Working within the Git repository created in Task 1.
- Working local Kubernetes
- Absolved Mentoring task 9 (Observability 101)

## Acceptance Criteria
- All new manifests, configurations, and theoretical markdown files are pushed to the Task 1 Git repository for review.
- Working implementation of distributed tracing and/or profiling.
- Demonstrated ability to trace a request through the microservices.
- Answered theoretical questions regarding tracing and profiling.

---

