# Subtask: Implement A Security Context On The Webapplication Deployment

## Purpose
Apply strict security contexts to the Task 1 deployments.

## Task Details & Parameters
Update the manifests to drop all capabilities, run as non-root, set read-only root filesystems, and apply necessary seccomp profiles.

## Acceptance Criteria
- Application continues to function correctly with restricted permissions.
