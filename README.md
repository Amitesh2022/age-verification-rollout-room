# Age Verification Rollout Room

## One-sentence benefit
Helps public authorities and wallet teams coordinate private, secure and interoperable proof-of-age rollouts.

## Live demo
Run the Java service and Angular application locally to use the complete experience.

## Screenshots
![age verification coordination workspace](docs/screenshot.png)

## Main features
Search rollout plans, create a regional rollout, progress readiness actions and monitor approval and high-priority gaps.

## Technology used
Angular, TypeScript, signals, computed state, server rendering, Spring Boot and Java.

## Installation instructions
Start the backend with `cd backend && mvn spring-boot:run`. In another terminal run `npm install && npm start`.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Digital authorities, identity-wallet teams, platforms and independent assessors need shared evidence for privacy, security and interoperability.

## Key workflows
Teams can find a rollout plan, add a validated national pilot and advance privacy and security work to approval.

## Angular framework highlights
The interface uses standalone components, signals, computed values, OnPush change detection, built-in control flow and SSR-safe loading.

## Java backend highlights
The Spring Boot service provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
Angular HttpClient connects signal-based state to the Java API and updates the visible board after every write.

## Accessibility and responsive behaviour
Semantic structure, labelled controls, visible focus, high contrast and compact responsive tables support varied users and devices.

## Verification commands
Use `npm test -- --watch=false`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains the Angular experience, `backend` contains the Java service, and `docs` contains verified media.

## Tradeoffs
Records are held in memory for demonstration speed; operational use would add identity, durable storage and trusted-provider integrations.

## Roadmap
Add trusted issuer lists, zero-knowledge proof checks, independent scrutiny, multilingual notices and audit-ready persistence.
