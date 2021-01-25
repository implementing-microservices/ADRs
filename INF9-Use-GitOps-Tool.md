# INF-9: Deploy Microservices Using a GitOps Deployment Tool
Date: 01-08-2020

## Status

Accepted

## Context

We need to decide on how microservices containers will be released into our Kubernetes system. This can be done manually, with scripts or through a dedicated tool.

## Decision

We'll use ArgoCD as a deployment tool for our microservices containers and changes. ArgoCD is a GitOps tool and its declarative style of release managemnt fits well with other tool and pattern choices we've made on this project.

## Consequences

Implementers will need to install and understand how to use ArgoCD for deployment. This increases the complexity of our infrastructure platform.
