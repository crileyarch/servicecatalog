# servicecatalog
Service Catalog Example

## Introduction

This repository is meant to create a simple story board for demonstrating ServiceNow Service Catalog / Portal capabilities in conjunction with Infrastructure Automation. The focus will be on demonstrating this functionality from the lense of an infrastructure engineer that leverages tools like Terraform, Ansible, Azure CLI, Google Cloud CLI etc. This individual is working closely with build engineers creating pipelines and test automation engineers that have stood up test automation infrastructure (e.g. Selenium Grid, JMeter). In the demonstrate the flow will be the following:

- Infrastructure Engineer needs to locate automation around an Azure Resource Group or a Google Kubernetes Engine Cluster.
- Engineering team is developing scripts, templates, config and placing them into a Git Repository.
- Engineering is tasked with surfacing this work up into a Service Catalog so that external parties can discover, interpret and consume the capabilities.
- Infrastructure Engineer goes to the Service Catalog Portal and navigates through the available automation to find specifically the capability they need. 
- Infrastructure Engineer reads the Knowledge Base Article which provides high level summary, detail summary, hyperlinks to the Git Repository where the scripts/templates/config is located. 
- Infrastructure Engineer decides on cloning the repo and running the scripts manually or selecting a quick <perform action> link which executes the automation for them.

## Example 1: Microsoft Azure Resource Group



## Example 2: Kubernetes Cluster (GKE)


## Artifacts

The artifacts for this work will include the Terraform templates which are stored in this repository along with a presentation that will be developed to articulate a Service Catalog notion leveraging ServiceNow capabilities.

