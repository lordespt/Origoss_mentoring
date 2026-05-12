# Subtask: Create A Github Sync Repo For Argocd

## Purpose
Bootstrap ArgoCD and manage the Task 1 application declaratively.

## Task Details & Parameters
Deploy ArgoCD. Use the Git repository created in Task 1 (which already contains the Kubernetes manifests) as the source of truth, and configure ArgoCD to sync from it.

## Acceptance Criteria
- ArgoCD successfully syncs the repository and deploys the Task 1 application.
