# toraaglobal-k8-lab
The project involves creating a Kubernetes cluster for a home lab experiment using Raspberry Pi devices.
***

Purpose

In this project, the focus is on conducting home lab experimentation with Raspberry Pi devices, but with the intention of deploying the resulting Kubernetes cluster in a highly available mode that can support production applications. The cluster will be configured to run a data pipeline for Extract, Transform, Load (ETL) operations, and enable model deployment. It will also support web applications and APIs for inferencing purposes.

To achieve the desired level of availability and performance, a 5-node cluster is set up, comprising two master nodes and three worker nodes. The use of persistent volumes and claims is employed to ensure data is retained across cluster restarts. Ansible is used to configure and manage the cluster.

Elastic Stack is used to provide cluster-wide monitoring and application logging, enabling effective management of the system. Service accounts with role bindings are used for authentication and authorization, which ensures security and privacy within the cluster. Overall, this project aims to create a robust and reliable Kubernetes cluster that can support production applications using Raspberry Pi devices.


