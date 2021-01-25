# MSE-5: Use Faux Git Submodules
Date: 01-08-2020

## Status

Accepted

## Context


## Decision

To check out repositories of individual microservices under the umbrella repository,
we use the open source project Faux Git Submodules. The idea is to make it easy to
descend into a subfolder of your workspace repository containing a microservice and
treat it as a fully functioning repository, which you can update, commit code in, and
push to. The basic intent is identical to that of regular Git submodules, except anyone
who has used them knows that the actual submodules can behave unpredictably and
tend to be major pains in the neck. Faux submodules, in our opinion, are much simpler
and work more predictably.

## Consequences

