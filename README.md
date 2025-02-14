## NOTICE: PROJECT IN MAINTENANCE MODE

As of the start of 2022, I have transitioned to a new role where I can no longer commit to improving or maintaining this project going forward. I am open to transferring the project to a new owner. If you are interested in taking ownership of the project please contact me on LinkedIn @ [charleszipp](https://www.linkedin.com/in/charleszipp/).

Alternative Extension available [here](https://marketplace.visualstudio.com/items?itemName=ms-devlabs.custom-terraform-tasks)

# Azure Pipelines Extension for Terraform

![Build Status](https://dev.azure.com/azure-pipelines-terraform-rc/azure-pipelines-terraform-rc/_apis/build/status/charleszipp.azure-pipelines-tasks-terraform?branchName=main)
![Visual Studio Marketplace Installs - Azure DevOps Extension](https://img.shields.io/visual-studio-marketplace/azure-devops/installs/total/charleszipp.azure-pipelines-tasks-terraform?label=marketplace%20installs)

This contains tasks for installing and executing Terraform commands from Azure Pipelines. These extensions are intended to work on any build agent. They are also intended to provide a guided abstraction to deploying infrastructure with Terraform from Azure Pipelines.

The tasks contained within this extension are:

- [Terraform Installer](/tasks/terraform-installer/README.md)
- [Terraform CLI](/tasks/terraform-cli/README.md)

This extension also contains views for the pipeline summary to help inspect actions performed by terraform.

The views contained within this extension are:

- [Terraform Plan](/views/terraform-plan/README.md)

## Telemetry Collection

The software may collect information about you and your use of the software and send to the repository owner. The repository owner may use this information to provide services and improve our products and services. You may turn off the telemetry as described below. 

### Disabling Telemetry Collection

Telemetry collection can be disabled by setting the `allowTelemetryCollection` property to `false`.

From classic pipeline editor, uncheck the `Allow Telemetry Collection` checkbox to disable
telemetry collection.

### Preferred Languages

We prefer all communications to be in English.
