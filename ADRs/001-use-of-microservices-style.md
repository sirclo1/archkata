# ADR 001: Use the microservice architecture style with containerization

## Status

Proposed.

## Context

Road Warrior is a new start-up company that wants to build the next generation online trip management. We assume it does not have a sizeable team, low cost maintenance and should be easy to adopt new technology. The architecture style should be simple

## Decision

We have decided to adopt a microservices architectural style. This will give us the following benefits:

- Modularity: Microservices are small, independent services that can be developed, deployed, and maintained separately. This makes it easier to add new features and fix bugs without impacting the entire system.
- Scalability: Microservices can be scaled independently to meet demand. This makes it easier to handle spikes in traffic and to scale up or down different parts of the system as needed.
- Resilience: Microservices are more resilient to failures than monolithic applications. If one microservice fails, the other microservices can continue to operate.
- Extensibility: Microservices are designed to be small and independent, which makes it easy to add new services or modify existing services without impacting the rest of the system. So, Microservices architecture can be extended easily to add new features or functionality.

## Rationale

We believe that the benefits of a microservices architecture outweigh the costs. We are committed to investing in the necessary tools and processes to develop and maintain a microservices architecture.
in using the microservice style.

## Risks

There are a number of risks associated with adopting a microservices architecture, including:

- Increased complexity: Microservices architectures can be more complex to develop and maintain than monolithic architectures.
- Communication overhead: Microservices need to communicate with each other, which can add overhead to the system.
- Testing overhead: Microservices need to be tested in isolation and in combination with other microservices, which can increase the testing overhead.

We are aware of these risks and we are committed to mitigating them. We will invest in the necessary tools and processes to develop and maintain a microservices architecture. We will also work with our team to ensure that they have the skills and knowledge necessary to develop and maintain microservices.

## Conclusion

We have decided to adopt a microservices architectural style. We believe that the benefits of a microservices architecture outweigh the costs. We are committed to investing in the necessary tools and processes to develop and maintain a microservices architecture.
