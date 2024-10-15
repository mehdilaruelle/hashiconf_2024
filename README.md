# A secure cloud agnostic in GitLab-CI with HCP Terraform and Vault

This repository has been made for the HashiConf 2024 for the [Hallway Track](https://www.hashicorp.com/conferences/hashiconf/agenda/10-15/a-secure-cloud-agnostic-in-gitlab-ci-with-hcp-terraform-and-vault).


## Abstract

Join us to build a secure and cloud-agnostic CI pipeline. We'll use GitLab-CI for our Git repository and CI/CD to deploy an application to AWS in this presentation. HCP Terraform will manage deployments, ensuring a seamless workflow. HCP Vault will secure CI secrets (AWS credentials, HCP Terraform token and database credentials) and application secrets. Additionally, HCP Terraform will configure Vault. This talk will demonstrate how to achieve secure, efficient deployments using these tools.

## Where to start?

This project is compose of 2 repository (added via `git submodules`):
1. **hcp-vault-tfc-init**: This Terraform folder is dedicated to create and configure the Vault server. This repository should be the first repository to be used before jumping to the next one.
2. **project-gitlab-terraform-vault**: This Terraform folder is dedicated to deploy an application with a Vault agent to retrieve secrets seamless.

## Slides of the talk

You can find the slides in [here](https://docs.google.com/presentation/d/1Vrt1NQT-BqJLbIdSgv9GaqNgRDmeo00V/edit?usp=sharing&ouid=116103448476400589337&rtpof=true&sd=true).

## Contact

You see something wrong ? You want extra information or more ?

Contact me: <contact@mehdilaruelle.com>