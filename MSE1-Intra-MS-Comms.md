# MSE-1: Avoid Microservices Calling Each Other Directly
Date: 01-08-2020

## Status

Accepted

## Context


## Decision

We don’t let ms-flights call ms-reservations to assemble the seating chart, and instead have the BFF API handle the interaction

## Consequences

