# INF-4: Use Github Actions for CI/CD Pipelines
Date: 01-08-2020

## Status

Accepted

## Context

In [INF-3](INF3-CICD-Infrastructure.md), we decided to incorporate CICD for our infrastructure changes. This requires us to select or build a tool to support this type of practice.

## Decision

We'll use Github's Actions feature for our infrastructure pipeline. While there are plenty of good CICD tools available, using Github Actions allows us to reduce the number of tools that readers have to setup as they will allready be using GitHub for source code management if they follow the examples we've provided.

## Consequences

Github Actions is not as mature as other dedicated CICD tools and relies heavily on a plug-in based ecosystem. This means that we'll need to continually evolve the pipeline as the platform itself changes.
