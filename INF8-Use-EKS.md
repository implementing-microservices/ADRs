# INF-8: Use a Managed Kubernetes Service
Date: 01-08-2020

## Status

Accepted

## Context

We plan to ship our microservices as containers and manage the container system with Kubernetes. We could run the Kubernetes system ourselves or we could use a cloud provider's managed Kubernetes service.

## Decision

We'll use AWS' Elastic Kubernetes Service to manage our Kubernetes system. This will greatly reduce the complexity of setting up our infrastructure and will allow implementers to get started faster.

## Consequences

AWS EKS is not free and using EKS will require implementers to incur billing charges - even if the services are not invoked.
