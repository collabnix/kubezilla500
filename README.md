# Kubezilla500 - Building the largest Kubernetes Community Cluster


<div align="center">
  <img src="https://github.com/collabnix/kubezilla500/blob/main/kubezilla500.png" alt="Logo" width="300"/>
</div>

Kubezilla is an ambitious project that aims to provide community members with an immersive learning experience in Kubernetes and related technologies. By building the largest Kubernetes Community Cluster, we aim to demonstrate the scalability and power of Kubernetes, while fostering collaboration and knowledge sharing within the community.We are aiming to build a largest Kubernetes Community Cluster and target to showcase it during Docker Bangalore Meetup event.


## Sponsorship Acknowledgment



<div align="center">
  <img src="https://github.com/collabnix/kubezilla500/blob/main/logo__on-white.svg" alt="Logo" width="200"/>
</div>

<div align="center">
  <img src="https://github.com/collabnix/kubezilla500/blob/main/cloud-drove-logo.jpg" alt="Logo" width="200"/>
</div>

<br>


We would like to extend our deepest gratitude to [Vultr](https://vultr.com) and [Cloud Drove](https://clouddrove.com) for their generous sponsorship towards the setup of our Kubernetes Cluster. Their support has been instrumental in enabling us to create a robust and scalable infrastructure to power our Kubezilla community cluster.




## Why are we doing this?

It's great opportunity for community members to learn, collaborate and contribute around Kubernetes and related technologies. As a team, we will learn how Kubernetes cluster is setup, how apps gets deployed over Cloud and what kind of microservices can be run possibly on these HUGE cluster nodes.Community members will learn how monitoring tools like Prometheus and Grafana can be deployed and fetch time-series metrics out of these HUGE cluster of nodes. In nutshell, it's a 1 day effort which will let every single individual to learn Kubernetes and understand its scalability.

## Sponsorship Opportunities

- [Click here](https://github.com/collabnix/kubezilla500/blob/main/sponsorship.md)

## How it works?

We invite contributors to help us build the largest Kubernetes Community Cluster by providing their FREE cloud instances or Raspberry Pi devices. Your contribution will help showcase the scalability and power of Kubernetes during the Docker Bangalore Meetup event.

You need to run the following Docker command to join your worker nodes:

```
sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.18 --server https://kubezilla.collabnix.com --token wlcj8nwx8ns92n69qbnk9f4kkmc7jkswcbgzpsm9hc4k6dxwjxdm8c --worker
```

**Node Specification:** XGB of RAM with X vCore. Please note that 512MB will not be enough for our testing requirements.

**Contribution Options:**

1. **Cloud Instance:** If you have a FREE cloud instance from AWS, Azure, GCP, or DigitalOcean, you can contribute it to our community cluster. By connecting your cloud instance to our cluster, you'll be part of this exciting initiative. 

2. **Raspberry Pi:** If you are familiar with connecting Raspberry Pi devices to a Kubernetes cluster, you can contribute your Raspberry Pi to our cluster. Your expertise will be invaluable in expanding the reach of our community project.

**How to Contribute:**

1. Fork this repository to your GitHub account.
2. Create a new branch with a descriptive name.
3. Add your cloud instance or Raspberry Pi contribution to the respective section in the README.
4. Submit a pull request to merge your changes into the main repository.

**Contribution Guidelines:**

- Please provide the specifications of your cloud instance or Raspberry Pi, including the RAM and vCore details.
- Include your full name, Twitter handle, and company name in the pull request description.
- Ensure that your contribution meets the node specification mentioned above.

We appreciate your support and contributions to make this project a success. Let's showcase the capabilities of Kubernetes together!

For any questions or assistance, please feel free to reach out to us. Thank you!



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
| [@anmolnagpal](https://github.com/anmolnagpal)                                                                                                             |               [CloudDrove](https://github.com/clouddrove)              |                    50                     |                                      |

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

| Name  of Submitter      |                Tool Name           |   Comments   |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------------------------------: | :-----------------------------------: | 
| [@ajeetsraina](https://twitter.com/ajeetsraina)                                                                                                            |               [Kubeview]([https://kubelabs.collabnix.com](https://github.com/benc-uk/kubeview))              |                    -                    |   


## References

- [List of curated Kubernetes Tools](https://kubetools.collabnix.com)
- [Kubernetes Tutorials](https://kubelabs.collabnix.com)
