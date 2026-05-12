# Subtask: Research And Implement Correct Configuration To Enable Correct Autoscaling In Argo Managed Resources

## Purpose
Resolve conflicts between HPA and GitOps.

## Task Details & Parameters
Configure ArgoCD to ignore replica count changes made by the HPA (from Task 2) so they don't constantly show as 'OutOfSync'.

## Acceptance Criteria
- ArgoCD sync status remains 'Healthy' even when HPA scales the application.
