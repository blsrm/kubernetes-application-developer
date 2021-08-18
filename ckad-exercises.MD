# Kubernetes Exercises


1. Deploy a pod named **nginx-448839** using the **nginx:alpine** image.

- Name: nginx-448839
- Image: nginx:alpine

2. Create a namespace named **apx-z993845**
- Namespace: apx-z993845

3. Create a new Deployment named **httpd-frontend** with 3 replicas using image **httpd:2.4-alpine**
- Name: httpd-frontend
- Replicas: 3
- Image: httpd:2.4-alpine

4. Deploy a **messaging** pod using the **redis:alpine** image with the labels set to **tier=msg**.

- Pod Name: messaging
- Image: redis:alpine
- Labels: tier=msg

5. A replicaset **rs-d33393** is created. However the pods are not coming up. Identify and fix the issue. Once fixed, ensure the ReplicaSet has 4 **Ready** replicas.

- Replicas: 4

6. Create a service **messaging-service** to expose the **redis** deployment in the **marketing** namespace within the cluster on port **6379**. Use imperative commands


- Service: messaging-service
- Port: 6379
- Use the right type of Service
- Use the right labels