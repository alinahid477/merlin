# Merlin - Wizard for Tanzu


<img src="images/logo-tanzuwizard.png" alt="Tanzu Wizard" width=200 height=210/> 


Tanzu Wizard is an initiative to improve user experience by simplifying interactions and day0 and day1 tasks with Tanzu Portfolio Components.

The way this is achieved are:
- Providing user with a bootstapped environment using docker.
- Automating a lot of manual steps with scripting (included in the bootstrap)
- Providing users with a simple and easy to follow wizard like interface to take input and display output where necessary.


## The goal:
- Provide user with a desired invironment through automating and simplifying 70%-80% of day0 tasks. A desired environment may look like
    - A application environment on k8s that uses tabbitmq
    - A build pipeline on k8s that user jenkins as CICD and/or TBS
    - k8s cluster on demand through request and approval
    - etc
- Through the usage of these bootstapped environment (based on docker) many day0 taks of deploying base components are simplified.
- By combining one or more of these bootstrapped docker an ondemand provision of a desired environment (as described above) can be created. The "combine part" can also be a wizard as a part of similar automation.



## Wizard Toolkits - What it does today

Below are some of the toolkits that are available to be consumed now

### vSphere with Tanzu Wizard

<img src="images/logo-vsphere-with-tanzu.png" alt="vSphere with Tanzu Wizard" width=100 height=110/>

Read here: [vSphere with Tanzu Wizard](https://github.com/alinahid477/vsphere-with-tanzu-wizard)


### Jenkins On K8S


<img src="images/logo-jenkinsonk8s.png" alt="Jenkins on K8S Wizard" width=100 height=110/>

Read here: [JenkinsOnK8S](https://github.com/alinahid477/jenkinsonk8s)


### RabbitMQ on K8S

<img src="images/logo-rabbitmqonk8s.png" alt="RabbitMQ on K8S Wizard" width=100 height=110/>

Read here: [RabbitMQOnK8S](https://github.com/alinahid477/rabbitmqonk8s)


### Tanzu Build Service Deployment Wizard

<img src="images/logo-tbswizard.png" alt="Tanzu Build Service Wizard" width=100 height=110/>

Read here: [TBSWizard](https://github.com/alinahid477/tbswizard)


### Tanzu Kubernetes Grid Wizard

Deployment Management Cluster and Workload cluster with Tanzu Kubernetes Grid Wizard.

<img src="images/logo-tkgonaws.png" alt="TKG on AWS Wizard" width=100 height=110/>                 <img src="images/logo-tkgonazure.png" alt="TKG on Azure Wizard" width=100 height=110/>



- [TKGonAWS](https://github.com/alinahid477/tkgonaws)
- [TKGonAzure](https://github.com/alinahid477/tkgonazure)


## Some handy ones

<img src="images/logo-tmcwizard.png" alt="TMC Wizard" width=100 height=110/>


- [TMCAttach](https://github.com/alinahid477/tmc-attach)
- [TMCRegistration](https://github.com/alinahid477/tmc-registration)


## Coming Soon

- TKG on vSphere
- vSphere wizard (tunnel, tmc registration, tmc attach, tanzu cluster)
