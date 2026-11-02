# Monolith to Microservices

## The change applied

Before, the application was organized as one monolith: its main features lived together in a single application. In a microservices architecture, those features are split into smaller services, each responsible for one area of the application.

## New project organization

The `services` folder separates LearnHub into services for authentication, users, courses, enrollments, payments, notifications, and analytics. This separation makes each area easier to develop and maintain independently.

The project also reserves an `api-gateway` for a single entry point to the services. The `shared` folder is intended for common libraries, schemas, and configuration. Docker and scripts folders provide places for container and development tooling.

## The main difference

In a monolith, a change to one feature is made within the same application as the other features. With microservices, each feature belongs to its own service, and services can be developed and deployed separately. They communicate through defined interfaces rather than sharing one application codebase.
