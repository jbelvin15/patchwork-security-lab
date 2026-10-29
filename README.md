# Patchwork: Application Security & AI Attack Lab

Patchwork is a hands-on security project built with Java and Spring Boot. It explores how web applications and AI-powered features can be exploited, and how to make them more secure.

The project uses a mock customer-data API and an AI-powered customer-support assistant to explore vulnerabilities such as broken access control, authentication flaws, and prompt injection. The goal is to understand how these attacks work, what risks they pose, and how to prevent them.

For each vulnerability, I'll document how to reproduce the attack, explain its impact, implement a fix, and write automated tests to help prevent it from happening again. I'll also integrate security scanning into a CI/CD pipeline to catch potential issues before deployment.

## Goals

- Get hands-on experience finding and exploiting application security vulnerabilities.
- Explore AI-specific risks, including prompt injection and unauthorized data access.
- Practice fixing vulnerabilities and verifying that the fixes work.
- Automate security checks as part of the development process.
- Document findings, attack methods, remediations, and lessons learned.

## Technology Stack

- **Language:** Java
- **Framework:** Spring Boot, Spring Security
- **API:** REST
- **AI:** AI model API
- **Testing:** Unit, integration, and security regression test
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
