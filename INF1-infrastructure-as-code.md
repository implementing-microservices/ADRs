# INF-1: Infrastructure as code

Date: 01-08-2020

## Status

Accepted

## Context

We need to decide how infrastructure changes will be made for the shared Microservices platform.

## Decision

We'll use the principle of infrastructure as code for all infrastructure changes. That means that all changes will need to be serialized as code or configuration that can be checked into a git repository.

## Consequences

No human operator infrastructure changes will be allowed. We'll need to invest in specialized tools and a language to treat infrastructure changes as code. Making changes will take longer than if we were to use a console or CLI.
