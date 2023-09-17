# ADR 003: Separate Domain Analytic & Report
## Status

Proposed.

## Context

Road Warrior reporting is part of analytical domain. We assume reporting it will be used by user by the end of the year and analytical will be used on demand, but it using the same data source or data warehouse and the logic processing might be completely different one of another. We assume to if reporting will draw lot of resource to processing the data.

## Decision

We have decided to seperate the reporting and analytical. The communication using REST, so each dev team can develop differently by use case and life cycle development on reporting and analytical.

## Rationale

We believe that the benefits of a microservices architecture outweigh the costs. We are committed to investing in the necessary tools and processes to develop and maintain a microservices architecture.
in using the microservice style.

## Risks

If the data source or the service from analytical goes down then reporting service will be failed to.

## Conclusion

We have decided seperate between reporting and analytical so we can make a pivot table separately and also it make easier developer using external tools
