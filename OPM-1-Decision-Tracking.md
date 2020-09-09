# OPM-1: Decision Tracking

Date: 01-08-2020

## Status

Accepted

## Context

We want to keep track of the key decisions we've made in the up and running Microservices build so that we know which decisions to re-consider in future builds. 

## Decision

We'll use Michael Nygard's Lightweight Architectural Decision Record format to log our key decisions. We'll manage the decision records as code and maintain a git repository to manage access and changes to them.

## Consequences

The decision record will become an important part of our system documentation and will be a starting point for new team members. It will need to be continually maintained as new decisions are made and old decisions change to avoid drift.
