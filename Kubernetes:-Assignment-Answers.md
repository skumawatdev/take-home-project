# Kubernetes:-Assignment-Answers

**Que.1. What are different types of services?**
      Ans.  ClusterIP, NodePort, LoadBalancer, ExternalName, Headless, Ingress.

**Que.2. What is a pod?**
      Ans.  A Pod is the smallest deployable unit in Kubernetes, containing one or more tightly coupled containers that share network and storage resources.
      
**Que.3. Create a Pod with the above-created custom image; when a pod dies, Kubernetes should automatically restart.**
      Ans.   
           


**Que.4.How to access the custom application with a specific port?**
      Ans.  You can expose the application using a Service of type NodePort or LoadBalancer and specify the port in the Service configuration, 
      and it will map to the port in the Pod.
