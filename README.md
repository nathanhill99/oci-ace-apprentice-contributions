# ACE Apprentice – OCI Product Usage Evidence

This repository contains supporting evidence for my Oracle ACE Apprentice Product Usage milestone.

The content below demonstrates practical hands-on usage of Oracle Cloud Infrastructure (OCI), including networking, compute, secure access, load balancing, storage, and backup configuration.

---

## 1. OCI VCN and Networking
**Summary:** This video demonstrates practical use of Oracle Cloud Infrastructure (OCI) networking services by building and validating a secure VCN design.

What is shown:
- Creation and validation of a Virtual Cloud Network (VCN)
- Configuration of required gateways, route tables and security controls
- Creation of dedicated public and private route tables
- Use of Network Security Groups (NSGs) as the recommended access control approach
- Validation that minimum required networking rules were configured for secure connectivity

Oracle services used:
- OCI Virtual Cloud Network (VCN)
- OCI Route Tables
- OCI Gateways
- OCI Network Security Groups (NSGs)

Purpose:
To demonstrate hands-on OCI networking configuration and secure network segmentation for public and private resources.  
**Video:** [Watch Video](https://1drv.ms/v/c/a459633800dba502/IQA7ScgQWRfXQLJ3XBWM52TUAXKhiqBO8mpt8usimdTKLT4?e=5GqmSj)

---

## 2. Public Compute Instance and SSH Access
**Summary:** This video demonstrates practical use of Oracle Cloud Infrastructure (OCI) compute and networking services by deploying a public instance and validating secure SSH access.

What is shown:
- Public OCI compute instance configuration
- Association of the correct Network Security Group (NSG)
- Restriction of SSH access to my public IP address only for improved security
- Validation of successful SSH connectivity using the instance details and SSH key

Oracle services used:
- OCI Compute
- OCI Network Security Groups (NSGs)
- OCI Networking

Purpose:
To demonstrate secure remote administration of a public OCI compute instance using SSH and source IP restriction.  
**Video:** [Watch Video](https://1drv.ms/v/c/a459633800dba502/IQD92Yl9KX5FQpPjdurzq6O6AZYWG1P3cEZrYvrrUYx-_8k?e=NFlASq)

---

## 3. Private Compute Instance via Jump Host
**Summary:** This video demonstrates practical use of Oracle Cloud Infrastructure (OCI) compute and networking services by securely accessing a private instance through a public jump host.

What is shown:
- Validation of private instance network placement and connectivity
- SSH key-based trust configuration between public and private instances
- Use of the public instance as a secure jump host
- Successful SSH access from the public instance to the private instance

Oracle services used:
- OCI Compute
- OCI Networking
- OCI Security Configuration

Purpose:
To demonstrate a secure access pattern for administering private OCI compute instances without exposing them directly to the internet.  
**Video:** [Watch Video](https://1drv.ms/v/c/a459633800dba502/IQA3CsR5Cr3oRYUS55Ap6EVkAQZO0ikvoKUzU2wOTrAhi9Y?e=WZtMNF)

---

## 4. OpenVPN and Secure Private Access
**Summary:** This video demonstrates practical use of Oracle Cloud Infrastructure (OCI) Marketplace, networking and compute services by deploying and configuring OpenVPN for secure private access.

What is shown:
- Deployment of an OpenVPN Marketplace instance within a private OCI network
- Use of a dedicated public load balancer to provide secure frontend access
- OpenVPN configuration and validation of private subnet access
- Confirmation that client internet and DNS settings remain unaffected
- Successful SSH access to a private instance only when connected through OpenVPN

Oracle services used:
- OCI Marketplace
- OCI Compute
- OCI Networking
- OCI Load Balancer

Purpose:
To demonstrate secure remote access to private OCI resources using a VPN-based access pattern.  
**Video:** [Watch Video](https://1drv.ms/v/c/a459633800dba502/IQAn8odI5Y5BSowSbnqTfeHdAePJnjtnHSAD_SvFYE4T_7w?e=xlFz4y)

---

## 5. HTTPD, PHP and Load Balancer Validation
**Summary:** This video demonstrates practical use of Oracle Cloud Infrastructure (OCI) compute, networking and load balancing services by deploying a test PHP web application and validating access through a load balancer.

What is shown:
- Configuration of a dedicated load balancer for HTTP traffic on port 80
- Installation and configuration of Apache HTTPD and PHP 8.1 on a private OCI instance
- Creation of a test PHP web page for validation
- Configuration of required load balancer and network access
- Successful browser access to the PHP test page via the load balancer URL

Oracle services used:
- OCI Compute
- OCI Load Balancer
- OCI Networking

Purpose:
To demonstrate application deployment and public access to a backend web service hosted on OCI infrastructure.  
**Video:** [Watch Video](https://1drv.ms/v/c/a459633800dba502/IQCCz-xVC--9QrJTzem1wxqcAQYKCF3cKk6fEFVFuTpcGvU?e=k0LLy1)

---

## 6. Block Volume Attachment and Backup Configuration
**Summary:** This video demonstrates practical use of Oracle Cloud Infrastructure (OCI) storage services by attaching, mounting and protecting an additional block volume.

What is shown:
- Creation of an additional 100GB block volume
- Successful iSCSI-based attachment to a private OCI compute instance
- Demonstration of volume mount and validation using standard Linux commands
- Evidence of successful attachment before and after mount operations
- Configuration of backup protection, including full backup, bronze backup policy and scheduled incremental backups

Oracle services used:
- OCI Block Volume
- OCI Compute
- OCI Backup Policies

Purpose:
To demonstrate hands-on OCI storage management, persistence and backup configuration for workload protection.  
**Video:** [Watch Video](https://1drv.ms/v/c/a459633800dba502/IQB8O5vILFUFSIj-YCI85gznAeoCxMl5gV2CkHQBwDI8gvw?e=hOvvoU)

---

## Oracle Cloud Services Demonstrated
- OCI Virtual Cloud Network (VCN)
- OCI Compute
- OCI Network Security Groups (NSGs)
- OCI Load Balancer
- OCI Block Volume
- OCI Backup Policies
- OCI Marketplace (OpenVPN)
