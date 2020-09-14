# Homework with Terraform
This time homework will require you to pick up and use Terraform to learn and deploy basic and commonly used infrastructure patterns.

The task seems simple on the outside: using Terraform deploy 2 Tier infrastructure into Oracle Cloud Infrastructure

## Requirements

Requirement section below :rotating_light:

### General
* Use Terraform
    * Use version 0.12.x or higher
* Use OCI (Oracle Cloud Infrastructure)

### Infrastructure
- Solution has to feature at minimum 2 Tiers: Web and Database
- Web tier has to have a minimum of 2 Virtual machines (OS does not matter much here)
- Web Tier has to have a Load Balancer
- Database Tier has to be accessible only from Web Tier
- Database Tier should be a cloud managed (PaaS)
- Solution should be secured with network security groups

## Things to consider

* Terraform state placement
    * Local (perfectly fine)
    * Remote
        * Terraform Cloud
        * Azure Blob Storage
        * AWS S3
        * other ?
* Where do you run this code
    * Your own PC (perfectly fine)
    * Azure DevOps
    * GitLab
    * Terraform Cloud
    * other ?
* Network security
* Availability domains


## Bonus points

- Compact reusable code using terraform modules
- Remote state
- Remote execution (Code is running on a hosted service)
- 3 Tiers

## Submitting

To review homework assignments we will need a link to your public Github repository. Please email them by responding to the homework email sender.

## :rotating_light: Oracle Cloud Account :rotating_light:

Oracle Cloud has a free trial and I urge you to register and use it. Free trial grants you $250 credit to try out various resources. However for this homework always free resources are sufficient.

However if you do not wish to sign up for OCI yourself we can offer a shared account with a limited budget, all you need to do is to provide your public key for us to set you up. All questions here can be answered by Nilsas and Jonas.
