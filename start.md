# Terraform associate 004


## Learn about Infrastructure as Code (IaC)

### Why use IAC? And why Terraform?
- Infrastructure as code is a mainstream pattern for managing infrastructure with configuration files rather than through a graphical user interface or through manual command line script sequences.


### What problem terrraforms fix?
- That really becomes the value. It’s really the versioning of it, the reusability of the code, and the ability to then do automation on top of it.


### In the scenario when, we "scale up to handle a load during a peak day, and then scale down at night to save on cost, because it’s not a fixed cost", uses Terraform is recommended?
- Yes, of course.


### What means HCL?
- hashicorp configuration language, you can use this languange to declare reuseble configuration


### What is the Provider function? how many providers exists? 
- Providers enable Terraform to work with virtually any platform or service with an accessible API.
- HashiCorp and the Terraform community have already written thousands of providers to manage many different types of resources and services


### Can you give examples of providers? and where que can find it?
- You can find all publicly available providers on the Terraform Registry, including Amazon Web Services (AWS), Azure, Google Cloud Platform (GCP), Kubernetes, Helm, GitHub, Splunk, DataDog, and many more.


### What are the stages that make up Terraform?
- Write: You define resources, which may be across multiple cloud providers and services. For example, you might create a configuration to deploy an application on virtual machines in a Virtual Private Cloud (VPC) network with security groups and a load balancer.
- Plan: Terraform creates an execution plan describing the infrastructure it will create, update, or destroy based on the existing infrastructure and your configuration.
- Apply: On approval, Terraform performs the proposed operations in the correct order, respecting any resource dependencies. For example, if you update the properties of a VPC and change the number of virtual machines in that VPC, Terraform will recreate the VPC before scaling the virtual machines.