# Labels and Selectors

## Overview of labels

Labels are key/value pairs that are attached to objects, such as pods.
the follwing pictures show some objects in AWS whih no labales.

<div align="center">
 <img src="images/image1.png" alt="IAM Policies" width="50%">
 </div>

## Adding Labels to Resource

<div align="center">
 <img src="images/image2.png" alt="IAM Policies" width="50%">
 </div>

## Overview of Selectors

Selectors allows us to filter objects based on labels.
Example:

1. Show me all the objects which has label where env: prod

<div align="center">
 <img src="images/image3.png" alt="IAM Policies" width="50%">
 </div>

2. Show me all the objects which has label where env: dev

<div align="center">
 <img src="images/image4.png" alt="IAM Policies" width="50%">
 </div>

## Kubernetes Perspective

There can be multiple objects within a Kubernetes cluster.
Some of the objects are as follows:
1. Pods
2. Services
3. Secrets
4. Namespaces
5. Deployments
6. Daemonsets

<div align="center">
 <img src="images/image5.png" alt="IAM Policies" width="50%">
 </div>

## Assigning Labels to Kubernetes Objects

<div align="center">
 <img src="images/image6.png" alt="IAM Policies" width="50%">
 </div>

 
