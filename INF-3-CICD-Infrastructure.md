# INF-3: Use a CICD Pipeline for Infrastructure Changes
Date: 01-08-2020

## Status

Accepted

## Context

In [INF-1](NF1-infrastructure-as-code.md), we decide to adopt the practice of infrastructure as code, but we need to decide how we'll apply those code changes to the system.

## Decision

We'll use the pattern of [continuous integration and continuous delivery](https://en.wikipedia.org/wiki/CI/CD) to apply infrastructure changes. This will be a dedicated pipeline for infrastructure changes that will exist in addition to any CICD pipelines that we deploy for the microservices code. Using CICD allows us to apply good code based change practices to the infrastructure code.

## Consequences

Incoporating CICD will require a set of tools and good practices that can support automoation and testing of code changes. We'll either need to build these tools ourselves or find a tools that fits our needs.
