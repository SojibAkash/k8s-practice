# k8s-practice
Here i share my k8s practices

Kubernetes: Kubernetes is an open-source system that provides users with the ability to manage, scale and deploy containerized applications.
Some features of k8s:

1.Self-Healing
2.Scaling
3.Secrets
4.Load Balancing

Kubectl: Kubectl is the Kubernetes command line tool that allows you to run commands against Kubernetes clusters. For example, you can use kubectl to deploy applications, inspect and manage cluster resources, and view logs.

k8s cluster: Red Hat Definition: "A Kubernetes cluster is a set of node machines for running containerized applications. If you’re running Kubernetes, you’re running a cluster. At a minimum, a cluster contains a worker node and a master node."

Node: A node is a virtual or a physical machine that serves as a worker for running the applications.

Deployment: A Kubernetes Deployment is used to tell Kubernetes how to create or modify instances of the pods that hold a containerized application.
A Deployment is a declarative statement for the desired state for Pods and Replica Sets. 

k8s services:In simpler words, it allows you to add an internal or external connectivity to a certain application running in a container. 

It Provides some features :
1.Load Balancing
2.Service Discovery ( Provide labels and selectors)
3.Expose to other world

Service type are three types:
1.ClusterIP
2.NodePort
3.LoadBalancer

Ingress: From Kubernetes docs: "Ingress exposes HTTP and HTTPS routes from outside the cluster to services within the cluster. Traffic routing is controlled by rules defined on the Ingress resource."

Ingress Controller: An implementation for Ingress. It's basically another pod (or set of pods) that does evaluates and processes Ingress rules and this it manages all the redirections.

Operators: "Operators are software extensions to Kubernetes that make use of custom resources to manage applications and their components. Operators follow Kubernetes principles, notably the control loop."

Secrets: Secrets let you store and manage sensitive information (passwords, ssh keys, etc.)

etcd: etcd is an open source distributed key-value store used to hold and manage the critical information that distributed systems need to keep running.

RBAC: RBAC in Kubernetes is the mechanism that enables you to configure fine-grained and specific sets of permissions that define how a given user, or group of users, can interact with any Kubernetes object in cluster, or in a specific Namespace of cluster. 

Namespaces: Namespaces allow you split your cluster into virtual clusters where you can group your applications in a way that makes sense and is completely separated from the other groups (so you can for example create an app with the same name in two different namespaces) 

CronJob: A CronJob creates Jobs on a repeating schedule. One CronJob object is like one line of a crontab (cron table) file. It runs a job periodically on a given schedule, written in Cron format. 

Helm: Package manager for Kubernetes. Basically the ability to package YAML files and distribute them to other users and apply them in the cluster(s).

Helm Charts: Helm Charts is a bundle of YAML files. A bundle that you can consume from repositories or create your own and publish it to the repositories. 
