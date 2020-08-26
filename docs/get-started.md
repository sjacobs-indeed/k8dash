---
layout: default
title: Get Started
permalink: /docs/get-started/
---

To run K8dash, see the [README](https://github.com/indeedeng/k8dash/blob/master/README.md). 

Once you have K8dash running, see the following quick start information. 

### Nodes

This section shows the list of servers and CPU / RAM used by each server. It can provide insights on server resource allocations. 

To get more details, click on a server. This shows which pods are running on that server. 

### Workloads

This section shows the deployments and CRON jobs. It can be very useful to monitor deployments. 

To get more details, click on the listed pods. 

In this view, you can: 
* Edit the pod configuration YAML
* View the documentation
* Delete a pod
* If enabled, you can SSH into the pod to view its logs

### Namespace

In this section, you can filter your cluster details by namespace. 

### Config Maps

A config map is a Kubernetes concept that allows you to set up configurations and tie them to deployments. 

### Service Accounts

In this section, you can manage users, roles, and permissions for your cluster. 

### Apply

This section allows you to enter YAML to make configuration changes to your Kubernetes cluster. 

### Other

K8dash also includes sections for Services, Replicas, Pods, Ingress, and Storage. Use the Ingress section to manage configurations, and the Storage section to manage persistent volumes and claims. 
