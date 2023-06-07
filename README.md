# Kubezilla500 - Building the largest Kubernetes Community Cluster


We are aiming to build a largest Kubernetes Community Cluster and target to showcase it during Docker Bangalore Meetup event.

![image](https://github.com/collabnix/kubezilla500/assets/34368930/f0ea1755-2793-48ff-80f9-79a8a7e4cf4c)




## Why are we doing this?

It's great opportunity for community members to learn, collaborate and contribute around Kubernetes and related technologies. As a team, we will learn how Kubernetes cluster is setup, how apps gets deployed over Cloud and what kind of microservices can be run possibly on these HUGE cluster nodes.Community members will learn how monitoring tools like Prometheus and Grafana can be deployed and fetch time-series metrics out of these HUGE cluster of nodes. In nutshell, it's a 1 day effort which will let every single individual to learn Kubernetes and understand its scalability.

## When? 

> We are targeting 8th July starting 9:00 AM till 5:00 PM for Kubezilla. 

| Activity  |      Date      |        Time        |
| :-------: | :------------: | :----------------: |
| Rehearsal | 5th July 2023 | 11:00 AM to 1:00 PM |
| Live  | 8th Jul 2023 | 9:00 AM to 4:00 PM |


## Contributors


| Name                                                                                                                                                       |                Company                | Number of Nodes<br>Expected to Contribute |             Machine Type             |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------------------------------: | :---------------------------------------: | :----------------------------------: |
| [@ajeetsraina](https://twitter.com/ajeetsraina)                                                                                                            |               [Collabnix](https://kubelabs.collabnix.com)              |                    10                     |                                      |


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


## List of application to be deployed

| Name         |                Submitter           |   Comments   |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------------------------------: | :-----------------------------------: | 
| [@ajeetsraina](https://twitter.com/ajeetsraina)                                                                                                            |               [Kubeview]([https://kubelabs.collabnix.com](https://github.com/benc-uk/kubeview))              |                    -                    |   

