# INF-6: Host Microservices in AWS
Date: 01-08-2020

## Status

Accepted

## Context

We'll be hosting Microservices in a cloud platform, but we'll need to decide which cloud platform to use.

## Decision

We'll use AWS and its managed services for our up and running microservices system. We've had success with all the major cloud providers on projects, but we've decided to use AWS because it is popular amongst practitioners.

## Consequences

Using AWS will result in a signficant amount of vendor lock-in, particularly when using managed services. This greatly reduces the portability of the solution. However, using AWS' managed services will reduce some of the complexity of the solution.
