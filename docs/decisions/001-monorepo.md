# ADR-001: Use a Monorepo

## Status

Accepted

## Decision

TravelOS will use a monorepository containing:

- Frontend
- Backend
- AI service
- Infrastructure
- Documentation

## Reason

The project is being developed as a single product and the services
share common development, documentation and deployment workflows.

A monorepo also simplifies local development and CI/CD during the
early stages of the project.

## Future Consideration

Services may be separated into independent repositories if the project
grows to a scale where independent lifecycle management becomes
beneficial.