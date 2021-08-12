# AVD Proof of Concept for Contoso

## Motivation
>*Guide a partner through an Azure Virtual Desktop (AVD) Proof of Concept (PoC) by applying Cloud Adoption Framework (CAF) principles.*
 

## We want to help you...:
- ... ask the right questions at the right time (especially for people that are new to AVD).
- ... by giving you samples, code artefacts + and a home (version control) for them.
- ... with a list of structured work items - so that an implementation can be done in a repetitive way.
- ... automate using pipelines to speed up deployments

## Screenshots
|  |  |  |
|--|--|--|
| ![Azure DevOps Demogenerator](./images/devopsdemogenerator.png) | ![New project](./images/newavdproject.png) | ![work items](/images/workitembacklog.png) |
| First we create a new project using the Azure Devops Demo Generator | The result: New AVD project... | ...with pefilled work items |
| ![code repository](./images/repository.png) | ![environment variable yaml file](./images/environmentfile.png) |![Azure DevOps pipelines](./images/pipelines.png) |  
| Automation code is in the code repository | Customize your environment to be rolled out by editing a variable file. |DevOps pipelines roll out AVD requirements and AVD artefacts. |  


## How?
- We use the **Boards** to **track what work needs to be done** - when and by whom. We've already added some things to the 'list'.
- We come with a suggested list of work items - not complete - so please make it your own (add, modify, delete). 
- The code **Repos**itory **already has some artefacts** (e.g. automation sample code used in the pipelines) that can be used to speed up deployments. It is **also** the **place** where **you** should **store generated artefacts** (excel, powerpoint, documentation,...) throughout a project. 
- We added some **Pipelines** to the project can be used to automate the Azure deployment e.g. of the landing zone parts (VNETs, subnets, VMs, images,...). They align with the user stories in the boards. 

## Getting Started
- [Challenge00 - Create an Azure DevOps project using the Azure DevoOps Demo Generator](./challenges/00-setup/readme.md)
- [Challenge01 - Create an Azure Service Principal to be used with Azure Devops](./challenges/01-createserviceprincipal/readme.md)
- [Challenge02 - Create an Azure Devops Service Connection using the service principal](./challenges/02-createserviceconnection/readme.md)
- [Challenge03 - Edit your environment file to change where & what will be deployed in the PoC](./challenges/03-editenvironmentfile/readme.md)

## Annotations
**This guide is by all means not complete !**  
If you have any 'useful' ;-) contributions - let us know.  
It is a repository for you to learn, showcase, adopt, copy,...  
Technically **we target avd native** (not AVD citrix nor avd vmware horizon) - i.e. the samples and code artefacts are tailored for the microsofts release of AVD. However you might still reuse some parts for 'the other' i.e. avd citrix - AVD vmware.
  
Best regards,  
the Team.

