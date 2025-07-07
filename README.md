# mine

This repository contains sample Kubernetes manifests and a collection of Azure DevOps pipeline
scenarios written in YAML. The pipelines are located under the `pipelines/` directory.

## Available pipelines

- **build.yml** - Restores dependencies, builds and tests a .NET project.
- **docker.yml** - Builds and pushes a Docker image to a container registry.
- **deploy.yml** - Applies Kubernetes manifests using a Kubernetes service connection.
- **terraform.yml** - Runs Terraform to provision Azure resources.
- **pr-validation.yml** - Example PR validation workflow.
- **multi-stage.yml** - Demonstrates a simple multi-stage pipeline.
- **extend-template.yml** - Example of extending a template with parameters and variable groups.

These files can be used as starting points for your own Azure DevOps pipelines.
Template files are located under `pipelines/templates/` and provide reusable steps that can be extended with parameters.
