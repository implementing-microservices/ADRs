# INF-10: Implement a Traefik Ingress Controller
Date: 01-08-2020

## Status

Accepted

## Context

Our microservices infrastructure will need a way to route messages from outside the newtork into sepcific Kubernetes hosted microservices. We'll need to pick an _ingress_ component that will do the message routing.

## Decision

We’ll use Traefik to route messages from the load balancer to microservices deployed in Kubernetes. This aligns well with our use of Traefik in the development stages. 

## Consequences

We'll need to setup Traefik as part of our infrastructure environment, resulting in added complexity for our build. In addition, we may need to support propreitary Traefik instructions in our Kubernetes deployment files.
