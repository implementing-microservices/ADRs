# OPM-2: Limit Team Size

Date: 01-08-2020

## Status

Accepted

## Context

The size of the teams in our microservices system is an important factor for co-ordination costs and speed. Setting a team size limit will help shape how we structure teams and the services that they work on.

## Decision

In our system, teams MUST have eight or less team members. If the team grows beyond this size, it SHOULD be split so that the team size can remain with the eight member boundary. The team size of eight is based on past working experience and anecdotal evidence from other implementers.

## Consequences

Limiting our team size to eight will have a few side effects:
1. The scope of a team's work will need to be similarily bounded - this means that any microservices they own must be manageable for a small team
2. As the system grows, we'll end up with a large number of small teams
3. A large number of small teams will in turn produce a large number of small components and services
