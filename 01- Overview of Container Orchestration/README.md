# Overview of Container Orchestration

During the initial times, users relied on manual container management or basic
scripts to handle tasks like deployment, scaling, networking, and monitoring.

![My Image](images/image1.png)

## Challenge 1 - Manual Scaling

If an application needed to handle higher traffic, developers had to manually
start additional containers.
This involved identifying which servers had enough resources, deploying new
containers, etc.


![My Image](images/image2.png)


## Challenge 2 - Lack of Fault Tolerance

If a container failed (e.g., due to a crash or resource exhaustion,), it wouldn’t
automatically restart without manual intervention in most of the cases.

![My Image](images/image3.png)

## Introducing Container Orchestration

*Container orchestration* automates the deployment, management, scaling, and
networking of containers.

![My Image](images/image4.png)

## Solving Challenge - Scaling

Orchestration tools CAN automatically scale containers up or down based on
defined policies and real-time traffic.

![My Image](images/image5.png)

## Solving Challenge - Fault Tolerance

Failed containers are automatically restarted or replaced to ensure high
availability.

![My Image](images/image6.png)

## Container Orchestration is LOT More

Container orchestration is the process of automating the networking and
management of containers so you can deploy applications at scale

- Provisioning and deployment
- Configuration and scheduling
- Resource allocation
- Load balancing and traffic routing
- Monitoring container health
- Keeping interactions between containers secure

There are multiple set of Container Orchestration tools available in the Industry.
Based on the organization and requirement, you can choose tools per
preference.

![My Image](images/image7.png)