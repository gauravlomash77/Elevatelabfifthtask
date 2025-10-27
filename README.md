# ElevateLab Task 5 — Build a Kubernetes Cluster Locally with Minikube

##  Objective
Deploy and manage applications in Kubernetes using **Minikube** and **kubectl** on Ubuntu.

---

##  Tools Used
- **Minikube**
- **kubectl**
- **Kubernetes**
- **Docker** (pre-installed)

---

##  Steps Performed

###  Start Minikube Cluster
minikube start
![Minikube-started](/screenshots/Minicube-started.png)

### Deployment and Nodes
kubectl get deployments
![Deployments-Nodes](/screenshots/Deployment-Nodes.png)

### Kubernetes Service 
kubectl get services
![Service](/screenshots/Service.png)

### Scaling Deployement
kubectl scale deployment nginx-deployment --replicas=3
![Service](/screenshots/Replica.png)

##  Learning Outcome
By completing this task,I:
- Understand the core concepts of Kubernetes.
- Learn how Minikube works locally.
- Know how applications are deployed and managed in a Kubernetes cluster.
- Gain confidence in basic Kubernetes operations and cluster management.

---

##  Conclusion
This task provided a hands-on introduction to Kubernetes and Minikube.  
It helped in understanding how modern cloud-native applications are deployed, scaled, and maintained efficiently using container orchestration.