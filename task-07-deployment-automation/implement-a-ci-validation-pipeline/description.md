# Subtask: Implement A Ci Validation Pipeline

## Purpose
Validate configurations automatically.

## Task Details & Parameters
Create a GitHub Actions (or similar) pipeline that runs YAML linting, Kubernetes schema validation (e.g., kubeval), and security scanning (e.g., checkov) on the GitOps repository on pull requests.

## Acceptance Criteria
- Pipeline runs and reports errors on invalid manifests.
