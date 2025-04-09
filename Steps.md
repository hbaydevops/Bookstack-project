Steps:
A. Backend: MariaDB
1. ConfigMap/Secret 
2. PV/PVC
3. Service: ClusterIP
4. Statefulset
    - Liveness Probe
    - Readiness Probe
5. Namespace


B. FrontEnd: Bookstack
1. ConfigMap/Secret 
2. PV/PVC
3. Service: ClusterIP
4. Ingress
5. Deployment
    - Liveness Probe
    - Readiness Probe
6. NetworkPolicy
7. Namespace
