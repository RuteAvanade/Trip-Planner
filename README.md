# Trip Planner

This repository includes a sample Flux CD setup for AKS. The infrastructure folder integrates the Bitnami Helm repository.

The dotnet folder contains a configuration for deploying a sample ASP.NET application using the App Gateway ingress controller.

To use this with an AKS cluster, start by installing the Flux extension. Then, create a Flux configuration with two Kustomizations: one pointing to the infrastructure directory and the other to the dotnet directory.
