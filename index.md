## Kubernetes




### Overview

# Introduction
1. What is Kubernetes

Cubernetes는 Docker 컨테이너용 오픈 소스 orchestration 시스템

- 시스템 클러스터에서 컨테이너 스케줄링 가능
- 한대의 머신에서 여러 개의 컨테이너를 실행할 수 있음
- 장기간 실행되는 서비스(예: 웹 애플리케이션)를 실행할 수 있음
- 쿠버네티스가 이러한 컨테이너의 상태를 관리함
- 특정 노드에서 컨테이너를 시작할 수 있음
- 컨테이너가 죽었을 때 다시 시작됨
- 컨테이너를 한 노드에서 다른 노드로 이동할 수 있음

2. Cloud / On-premise setup
3. Cluster Setup
4. Building Containers

# Kubernetes Basics
1. Node Architecture
2. Scaling pods
3. Deployments
4. Services
5. Labels
6. Healthchecks
7. ReadinessProbe
8. Pod State & LifeCycle
9. Secrets
10. WebUI

# Advanced topics
1. Service auto-discovery
2. ConfigMap
3. Ingress
4. External DNS
5. Volumes
6. Pod Presets
7. StatefulSets
8. Daemon Sets
9. Monitoring
10. Autoscaling
11. Node Affinity
12. InterPod (Anti-)Affinity
13. Taints and Tolerations
14. Operators

# Administration
1. Master Services
2. Quotas and Limits
3. Namespaces
4. User Management
5. RBAC
6. Networking
7. Node Maintenance
8. High Availability
9. TLS on ELB

# Packaging
1. Introduction to Helm
2. Creating Helm Charts
3. Helm Repository
4. Building & Deoloying

# Extras
1. kubeadm
2. TLS Certificates with cert-manager
