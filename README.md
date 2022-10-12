# What The Hack - CICD with Github and Azure

## Introduction

## Learning Objectives

## Challenges
- [Challenge 0](./Student/challenge00.md) - Setup and Introduction
- [Challenge 1](./Student/challenge02.md) - Infrastructure as Code **OR** Infrastructure deployment
- Webapp with logic to send to proper storage (gcp/azure), access tokens... maybe service principals
- [Challenge 2](./Student/challenge03.md) - Github Actions (fundamentals / setup, protected branches)
- [Challenge 3](./Student/challenge04.md) - Github Actions - Continuous Integration
- [Challenge 4](./Student/challenge05.md) - Github Actions - Continuous Integration - Build and push container image to container registry
- [Challenge 5](./Student/challenge06.md) - Github Actions - Continuous Integration - Reusable Workflows, approval gate
- [Challenge 6](./Student/challenge07.md) - Github Actions - Continuous Delivery to Microsoft Azure
- [Challenge 7](./Student/challenge08.md) - Monitoring: Application Insights *(maybe)*
- [Challenge 8](./Student/challenge09.md) - Security *(maybe)*

| # | Title | Description | Est Time |
|---|---|---|---|
| 1 | Setup and Introduction | Introductions and workstation setup | xx min |
| 2 | Infrastructure Deployment | Deployment of dev environment via azure cli | xx min |
| 3 | Github Actions  | Overview and setup (inc dependabot, credentials and secrets) | xx min |
| 4 | Github Actions - CI - Build Step  | Build application | xx min |
| 5 | Github Actions - CI - Test Step | Light testing of the application | xx min |
| 6 | Github Actions - CI - Release Step | Push container to registry | xx min |
| 6 | Github Actions - CI - Improve workflows | Addition of reusable workflows | xx min |
| 7 | Github Actions - CD - Deploy | Deploy application to Azure | xx min |

wish list
- dependabot
- credentials to deploy to k8s and python library server (github secrets and fuzzing)
- notifications to slack (ex: build, test fails)
- validation
- GitOps, CI infra/app testing, integration env where all the code comes together
- monitoring 
  - k8s, VM dashboard
  - request more resources than the pods need... mostly on cpu
  - ambassador in use
  - TLS services, K8s... terminate at LB and http
  - app registration

## Prerequisites
- Your own Azure subscription with **owner** access.
- Ability to create Azure AD service principal
- Github account
- [Visual Studio Code](https://code.visualstudio.com)
- [Git SCM](https://git-scm.com/download)

## Repository Contents
- `../Student`
  - Student Challenge Guides
- `../Student/Resources`
  - Student's resource files, code, and templates to aid with challenges

## Considerations
 -

## Contributors
- Eric Leonard

## License
This repository is licensed under MIT license. More info can be found [here](https://github.com/erleonard/gps-cicd-gh-azure/blob/main/LICENSE).