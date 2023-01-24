# kubezilla500


## Why are we doing this?

It's great opportunity for community members to learn, collaborate and contribute around Kubernetes and related technologies. As a team, we will learn how Kubernetes cluster is setup, how apps gets deployed over Cloud and what kind of microservices can be run possibly on these HUGE cluster nodes.Community members will learn how monitoring tools like Prometheus and Grafana can be deployed and fetch time-series metrics out of these HUGE cluster of nodes. In nutshell, it's a 1 day effort which will let every single individual to learn Kubernetes and understand its scalability.

## When? 

> We are targeting 21st Feb starting 2:00 PM till 4:00 PM for Kubezilla. 

| Activity  |      Date      |        Time        |
| :-------: | :------------: | :----------------: |
| Rehearsal | 21st Feb 2023 | 11:00 AM to 1:00 PM |
| Live  | 27th Feb 2023 | 2:00 PM to 4:00 PM |


## What's mininum requirements of a node?

Nodes can either be physical, virtual, IoT or Desktop system.
  

- 2 GB or more of RAM per machine (any less will leave little room for your apps)
- 2 CPUs or more
- Full network connectivity between all machines in the cluster (public or private network is fine)
- Unique hostname, MAC address, and product_uuid for every node. See here for more details.
- Certain ports are open on your machines. See here for more details.
- Swap disabled. You MUST disable swap in order for the kubelet to work properly.
- TCP	Inbound	10250	open for Kubelet API	
- TCP	Inbound	30000-32767 open for NodePort Services
