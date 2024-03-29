<img src="src/OpenShift.png" height="105" width="105">

# Introductory material

 <a href="https://cloud.google.com/containers/">Virtualization vid Containers</a> 
 and <a href="https://www.docker.com/resources/what-container">Docker</a>
 
 Video: <a href="https://www.ibm.com/cloud/container-service">Kubernetes and container orchestration</a> 

Video: [Kubernetes and OpenShift: What's the Difference?](https://www.ibm.com/cloud/blog/new-builders/kubernetes-and-openshift)

<a href="https://cloud.ibm.com/catalog">IBM Cloud</a>

Video: [IBM Cloud Kubernetes Service](https://www.ibm.com/cloud/container-service)

[Introduction to Containers](https://www.ibm.com/cloud/learn/containers)

[Kubernetes and OpenShift](https://www.ibm.com/cloud/blog/new-builders/kubernetes-and-openshift)

[Containers and Docker](https://www.ibm.com/cloud/garage/content/course/containers-and-docker/2)


# OpenShift

Videos, workshop: [What is OpenShift?](https://www.openshift.com/learn/what-is-openshift)
Red Hat OpenShift is a leading hybrid cloud, enterprise Kubernetes application platform

Videos, workshop: [Understanding OpenShift](https://github.com/nheidloff/openshift-on-ibm-cloud-workshops/blob/master/1-understanding-openshift/README.md#understanding-openshift)

[Red Hat OpenShift on IBM Cloud](https://cloud.ibm.com/docs/openshift?topic=openshift-why_openshift) is an extension of the IBM Cloud Kubernetes Service, where IBM manages the OpenShift Container Platform for you.

This repository holds a series of workshops that help you as a developer to become familiar with Red Hat OpenShift, how it can be deployed on the IBM Cloud, and how to deploy applications on and with OpenShift.

In order to run these workshops, you need an IBM Cloud account.

### [Workshop 1: Understanding Openshift](https://github.com/LennartFr/openshift-on-ibm-cloud-workshops#workshop-1-understanding-openshift) 
Note: We will not got thru Workshop 1 because it doesn't run on IBM Cloud, only on the Red Hat cloud.

### [Workshop 2: Deploying Java Microservices to OpenShift on IBM Cloud](https://github.com/LennartFr/openshift-on-ibm-cloud-workshops#workshop-2-deploying-java-microservices-to-openshift-on-ibm-cloud)
Note: For Workshop 2: we will only go thru Lab 1,4,5,6. 

<hr>

### [Resources and Next Steps](https://github.com/nheidloff/openshift-on-ibm-cloud-workshops#resources-and-next-steps)

# Minishift

Labs: [Minishift 101](https://github.com/IBMDeveloperUK/minishift101)

https://docs.okd.io/latest/minishift/using/basic-usage.html#diagram-minishift-architecture

[Launch Minishift](https://computingforgeeks.com/how-to-run-local-openshift-cluster-with-minishift/)

## Intro https://www.redhat.com/sysadmin/learn-openshift-minishift

OKD is the Origin Community Distribution of Kubernetes that powers Red Hat Open Shift

Minishift is a tool that helps you run OKD locally by launching a single-node OKD cluster inside a virtual machine. With Minishift you can try out OKD or develop with it, day-to-day, on your local machine.

You can run Minishift on the Windows, macOS, and GNU/Linux operating systems. Minishift uses libmachine for provisioning virtual machines, and OKD for running the cluster.

Minishift was created by the OKD community project, which was formed to separate the product that relies upon Red Hat's infrastructure from the technology available to everyone. This community is the upstream origin of OpenShift and their Minishift tool allows you to run a containerized single-node cluster so you can develop for Kubernetes on your local machine.

Minishift and OpenShift are very different, but Minishift is nevertheless a powerful introduction to the concept of running a cluster, creating projects, monitoring tasks, and maintaining a cloud infrastructure.
 
# Getting started with minishift.  
### https://docs.okd.io/latest/minishift/getting-started/quickstart.html

# Tips

eval $(minishift oc-envp
