# INF-2: Use Terraform for Infrastructure Changes
Date: 01-08-2020

## Status

Accepted

## Context

In [INF-1](NF1-infrastructure-as-code.md), we decide to adopt the practice of infrastructure as code. To be effective, we'll need to identify tools and patterns to support this method of operation and change.

## Decision

We'll use Hashicorp's Terraform tool to construct and apply our infrastructure changes. Terraform uses a declarative model for changes which we prefer. Terraform is also popular amongst implementers and we've had success using it on projects.

## Consequences

Using Terraform means that all our infrastructure code will need to be written in Hashicorp's HCL language. If we want to chagne tools in the future, we'll need to rewrite all of our infrastructure code to be compatible with a new tools' langauge.
