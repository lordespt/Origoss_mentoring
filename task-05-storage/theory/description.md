# Subtask: Theory

## Purpose
Understand Kubernetes storage primitives.

## Task Details & Parameters
Research Volumes, PersistentVolumes (PV), PersistentVolumeClaims (PVC), StorageClasses, and CSI drivers.

## Acceptance Criteria
Please provide detailed answers to the following questions in a markdown file:

1. Explain the difference between ephemeral storage and persistent storage in Kubernetes.
2. What happens to the data in an `emptyDir` volume when a Pod is deleted or crashes?
3. Define PersistentVolume (PV) and PersistentVolumeClaim (PVC). How do they interact?
4. What is a StorageClass, and how does it enable dynamic provisioning of volumes?
5. Describe the different access modes for PVs (`ReadWriteOnce`, `ReadOnlyMany`, `ReadWriteMany`, `ReadWriteOncePod`).
6. What is the Reclaim Policy of a PV, and what is the difference between `Retain` and `Delete`?
7. Explain the purpose of the Container Storage Interface (CSI). Why was it introduced?
8. How does a block storage solution differ from a file system storage solution in Kubernetes?
9. What are the trade-offs of using hostPath volumes in a multi-node cluster?
10. Describe the architecture of a distributed storage system like Ceph or Longhorn.
11. What is volume snapshotting, and how is it supported in Kubernetes?
12. How does storage topology/node affinity affect pod scheduling when using local persistent volumes?
13. Explain the difference between `VolumeBindingMode: Immediate` and `VolumeBindingMode: WaitForFirstConsumer`.
14. What is the purpose of the `volumeName` field in a PVC?
15. Describe how Resizing a PersistentVolumeClaim works dynamically.
16. What is a projected volume in Kubernetes?
17. How does OpenEBS local PV differ from standard hostPath volumes?
18. Explain the concept of Data Locality and why it matters for database workloads in Kubernetes.
19. What are the common failure scenarios for distributed storage like Ceph in a Kubernetes cluster?
20. How does backup and restore of Persistent Volumes work using the VolumeSnapshot API?