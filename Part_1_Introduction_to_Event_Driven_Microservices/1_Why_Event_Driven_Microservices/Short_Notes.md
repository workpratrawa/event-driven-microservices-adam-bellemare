## Basics
1. Message Passing Systems
    - Generally Point to Point
    - Message removed after consumption as intended consumer has already consumed.
2. Event Driven Architecture:
    - Broadcast
    - Usually retained, consumer track offset.
    - Other consumers can read it as they require
3. Sync vs Async communication
4. Diagram: Figure 1-1. A simple two-input, one-output event-driven microservice, with its own internal state store

## Intro to Domain Driven Design and Bounded Context
1. Domain
2. Subdomain
3. Bounded Contex
4. Diagram: Figure 1-2. Domains, subdomains, bounded contexts, and microservices

## Communication Structures in Traditional Computing
### Problem Statement:
New business requirement which is somewhat related to exisiting service but is also different enough.

Two options:
- Create new service
- Extend existing service

### Option: Make a New Service:
- CONs:
    - Requires old data
    - No process of launching a new service

- PROs:
    - Modularity and Independent System

