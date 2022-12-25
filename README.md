
# Terraspace Azure Cloud Project

This is a Terraspace project. It contains code to provision Cloud infrastructure built with [Terraform](https://www.terraform.io/) and the [Terraspace Framework](https://terraspace.cloud/).

## Deploy

To deploy all the infrastructure stacks:

    terraspace all up

To deploy individual stacks:

+ __terraspace up demo__ command deployed resource group that named dev-eastus, storage account and container.

+ __TS_ENV=qa terraspace up demo__ command deployed resource group that named qa-eastus, storage account and container.

+ __ARM_LOCATION=centralus TS_ENV=qa terraspace up demo__ command deployed resource group that named qa-centralus, storage account and container.

+  __terraspace up production__ command deployed resource group that named production_rm1 in canadacentral



## Terrafile

To use more modules, add them to the [Terrafile](https://terraspace.cloud/docs/terrafile/).
