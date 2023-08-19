# Kubernetes-learning
The basic fundaments of kubernetes which I am learning

Kubernetes-k8s
>Built by Google
>Docker-underlying container technology
>Nodes-A machine(physical or virtual) on which kubernetes is installed.
>Worker machines-where containers are launched by k8s.
>Master-A node with k8s installed and configured as master, which is responsible for managing workernodes

Node components:
-API server:  a REST API supporting basic CRUD operations on API objects. It basically acts as a frontend for k8s where users can interact<br>
-etcd: a distributed key-value storage system (etcd) as its backend for storing all cluster state and data<br>
-scheduler: responsible for distributing work load across multiple nodes<br>
-controller: responsible for noticing and responding when a node,container or an endpoint goes down.<br>
-container runtime: Underlying software to run containers like docker.<br>
-kubelet: an agent that runs on each node in a cluster.<br>

Master node consists of :
API server,etcd,scheduler,controller,container runtime,kubelet

Worker node consists:
container runtime,kubelet

