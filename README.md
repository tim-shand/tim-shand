# Hello! I'm Tim :wave:

## About Me

- I enjoy designing, building and automating systems.
- Over a decade of experience under my belt in support and engineering roles.
- Fond of repurposed tech (Raspberry Pi, Mini-PCs etc).
- Home lab enthusiast interested in Cloud, DevOps, GitOps, IaC, scripting, Proxmox, self-hosting.

## :books: Currently Learning

- Developing IaC and GitOps skills with Terraform, Ansible and automation pipelines. 
- Cloud architecture, network design and service integration.
- Linux systems, management and administration.

## :building_construction: Currently Building

- Refining my Azure platform landing zone.  
- Continuously building and tweaking my on-prem home lab.

## :wrench_and_hammer: Projects

**[Azure Platform LZ](https://github.com/tim-shand/azure-platformlz-custom)**

- Custom Azure platform landing zone, inspired by enterprise-scale architecture and CAF guidelines.
- Designed to be light-weight and cost efficient, utilising free or low-cost SKUs where applicable.
- Deployed in stacks (Management, Governance, Connectivity) with independent state files maintaining workload isolation.
- Bootstrapped via PowerShell script to deploy initial resources into Azure and GitHub repository.
- IaC automation using Terraform and GitHub Actions workflows.
- Dedicated service principal with custom RBAC role, utilising Federated Credentials (OIDC), enabling secure authentication during workflow execution.

**[Private Cloud Hypervisor Cluster (Home Lab)](https://github.com/tim-shand/homelab)**

- Multi node hypervisor cluster running Proxmox VE automated with Terraform and Ansible.
- Replication and high-availability configured for production workloads.
- Software-defined networking with VNet and VLANs configured in code.
- OPNsense providing network firewall, VLANs, DNS and routing functionality.
- Personal home lab environment for self-hosting and training.
