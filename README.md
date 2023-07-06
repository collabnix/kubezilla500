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

## How to add my node?

You need to run the following Docker command to join your worker nodes:

## For Cloud Instance [Ubuntu 20.04 LTS]

```
sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.18 --server https://kubezilla.collabnix.com --token wlcj8nwx8ns92n69qbnk9f4kkmc7jkswcbgzpsm9hc4k6dxwjxdm8c --worker --label node=cloud --label name=kubezilla
```

## For adding Laptop [Ubuntu 20.04 LTS]

```
sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.18 --server https://kubezilla.collabnix.com --token wlcj8nwx8ns92n69qbnk9f4kkmc7jkswcbgzpsm9hc4k6dxwjxdm8c --worker --label node=laptop --label name=kubezilla
```

## For adding Docker Desktop

```
sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.18 --server https://kubezilla.collabnix.com --token wlcj8nwx8ns92n69qbnk9f4kkmc7jkswcbgzpsm9hc4k6dxwjxdm8c --worker --label node=dd --label name=kubezilla
```

## For PWD

We suggest you to add only one instance per session so that there is not much pressure on the overall platform

```
sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.18 --server https://kubezilla.collabnix.com --token wlcj8nwx8ns92n69qbnk9f4kkmc7jkswcbgzpsm9hc4k6dxwjxdm8c --worker --label node=pwd --label name=kubezilla
```

## For PWK

We suggest you to add only one instance per session so that there is not much pressure on the overall platform

```
sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.18 --server https://kubezilla.collabnix.com --token wlcj8nwx8ns92n69qbnk9f4kkmc7jkswcbgzpsm9hc4k6dxwjxdm8c --worker --label node=pwk --label name=kubezilla
```

## For RaspberryPi/Jetson Nano


```
sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.18 --server https://kubezilla.collabnix.com --token wlcj8nwx8ns92n69qbnk9f4kkmc7jkswcbgzpsm9hc4k6dxwjxdm8c --worker --label node=iot --label name=kubezilla
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

                                 
| S. No | Name                      | Company                      | Node Type       | Node Count |
| ---|  ---------------------------|------------------------------|-----------------|------------|
| 1| Ajeet Singh Raina         | Docker                       | Cloud           | 10+        |
| 2 |Anmol Nagpal              | Cloud Drove                  | Cloud           | 50         |
| 3 |Kasibhatla Avinash        | Dexra solutions              | Laptop          | 5+         |
| 4 |shubhendu                 | TCS                          | Cloud Instance  | 1          |
| 5 |Krishna Hrithik           | Opentext                     | Laptop          | 1          |
| 6 |Sivakumar M               | Standard Chartered Bank      | Cloud Instance  | 5+         |
| 7 |Raji reddy K              | Progressive                  | Laptop          | 1          |
| 8 |Sujit Neb                 | BMC Software                 | Laptop          | 1          |
| 9 |shubha banerjee           | hdfc bank                    | Laptop          | 1          |
| 10 |OMID                      | Asan pardakht                | Bare Metal      | 10+        |
| 11 |Varun Bhatia              |                              | Laptop          | 1          |
| 12 | Sridhar keshab Senapati   | Searce                       | Cloud Instance  | 5+         |
| 13 |Aniket Banerjee           | Infosys                      | Cloud Instance  | 5+         |
| 14 | Gabriel Martins           | ACM                          | Cloud Instance  | 5+         |
| 15 | Rohit Ghumare             | Solo                         | Laptop          | 10+        |
| 16 | Kamlesh Rao               | SPHood                       | Laptop          | 10+        |
| 17 | Aravindhan Anandhavel     | Global Magnit                | Laptop          | 1          |
| 18 | Neetu Mallan              | EZOps Technologies           | Laptop          | 5+         |
| 19 | Lal Krishna               | Stickybit Technologies       | Bare Metal      | 5+         |
| 20 | Rutwik Kinagi             | Infosys Limited              | Laptop          | 5+         |
| 21 | Yashvi Kothari            | NA                           | Cloud Instance  | 1          |
| 22 | Gaganpreet Singh          | VMware                       | Cloud Instance  | 1          |
| 23 | Harsha Vardhan            |                              | Cloud Instance	| 1          |
| 24 | Sanaz Baniasadi           | 		                          | Cloud Instance	| 50+        |
| 25 | Rajendra G                |	Self                        | Laptop          |	1          |
| 26 | Raseel Bhagat             | Zymr                         | Cloud Instance  | 5+         |
| 27 | Unni P                    | Self                         | Laptop          | 5+         | 
| 28 | Sangam Biradar             | Deepfence                   | Cloud Instance  | 10+        |
| 29 | Geno Thomas               | IBM                          | Cloud Instance  | 3          |
| 30 | Karan Singh               | Scogo                        | Bare Metal      | 1          |

## What's mininum requirements of a node?

Nodes can either be physical, virtual, IoT or Desktop system.
  

- 2 GB or more of RAM per machine (any less will leave little room for your apps)
- 2 CPUs or more
- Ubuntu 20.04 LTS as operating system
- Full network connectivity between all machines in the cluster (public or private network is fine)
- Unique hostname, MAC address, and product_uuid for every node. See here for more details.
- Certain ports are open on your machines. See here for more details.
- Swap disabled. You MUST disable swap in order for the kubelet to work properly.
- TCP	Inbound	10250	open for Kubelet API	
- TCP	Inbound	30000-32767 open for NodePort Services

## Ports required to be open on Worker Nodes

```
TCP     10250       Kubelet API
TCP     10255       Read-Only Kubelet API
```

## List of application to be deployed

| Name                      | Application Name       | 
|---------------------------|------------------------------|
| Ajeet Singh Raina         | Kubeview                     |
| Anmol                     | Grafana                      |



## FAQs

## 1. How shall I contribute?

Assuming that you have Docker installed in your system, you can run the below command to get your node connected to our Cluster:

```
sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.18 --server https://kubezilla.collabnix.com --token wlcj8nwx8ns92n69qbnk9f4kkmc7jkswcbgzpsm9hc4k6dxwjxdm8c --worker
```

## 2. Do I need to pay?

No, we recommend you to use Free Tier so that you don't need to pay anything from your pocket.
You can even use [PWD](https://play-with-docker.com) or [PWK](https://play-with-k8s.com) instance(free) but do note that these instances are usually operational only for 4 hours time.

## 3. Can I use my AWS/GCP/Azure Credits to get the nodes added?

Yes, you can use those free credits. It's a matter of choice

## 4. How many maximum nodes can I contribute?

There is no restriction. You can add as many nodes as you can.

## 5. Which ports are required to be open on worker nodes?

```
TCP     10250       Kubelet API
TCP     10255       Read-Only Kubelet API
```

## 6. I have added nodes. How can I see the nodes added?

We are currently working on a Visualization tool to allow you to visualize the overall Kubernetes Cluster. Stay tuned.

## 7. Which OS needs to use for setting up worker nodes?

We recommend you to use Ubuntu 20.04 LTS as operating system because of cgroup driver issue.

## References

- [List of curated Kubernetes Tools](https://kubetools.collabnix.com)
- [Kubernetes Tutorials](https://kubelabs.collabnix.com)
