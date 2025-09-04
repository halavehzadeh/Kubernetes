# Overview of kubectl

The Kubernetes command-line tool, kubectl, allows you to run commands
against Kubernetes clusters.

![My Image](images/image1.png)

Kubectl needs two important details while connecting to Kubernetes Cluster
1. DNS / IP Address of Kubernetes Control Plane
2. Authentication Credentials.

![My Image](images/image2.png)

Kubectl by default will look for the kubeconfig file in a file named config inside
.kube folder in your home directory.

```
~/.kube/config

```

![My Image](images/image3.png)

You can also refer to custom config file using the --kubeconfig flag

![My Image](images/image4.png)