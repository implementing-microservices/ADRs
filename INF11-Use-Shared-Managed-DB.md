# INF-11: Use Shared and Managed Database Services
Date: 01-08-2020

## Status

Accepted

## Context

We need to decide on storage options and implementations for microservices. We could allow microservice teams to own and operate their own databases, or we could provide a shared database servcie that they can use.

## Decision

The platform team will create Terraform-based modules to provision AWS hosted and managed database services for each environment. Microservices will have shared access to these database instance, but can still own and manage their own data and data structures.

## Consequences

The platform team will need to own and operate the database services by coordinating with microservices teams. They'll need to ensure that the data services meet the needs of implementing teams and that the service is easy to use, reliabile, performant and maintained. Using a manged service helps to reduce the costs of this ownership.
