# CashFlow

Managing your money has never been easier! CashFlow is a modern and intuitive financial tracking app designed to help you take control of your finances effortlessly.

With a friendly user interface you will be able to register your incomes and expenses and with the help of generated graphics you will be able to understand what is happening on your financial life.

# Summary

- [Project Architecture](#project-architecture)
  - [APIs](#apis)
  - [UI](#ui)
  - [Utilities](#utilities)
  - [Docker](#docker)
- [Project Organization](#project-organization)
    - [Documentation](#documentation)
    - [Good Practices](#good-practices)
    - [Technologies](#technologies)
- [Containerization](#containerization)

# Project Architecture

The project is based on microservices architecture where we will have multiple APIs each one with your responsibility strongly defined. 

The chosen architecture will make the app easy to scale up, improve maintenance and facilitate errors identification and treatment.

### APIs

- [API-Auth](https://github.com/Peralta-CashFlow/CashFlow-API-Auth);

### UI

- [CashFlow-UI](https://github.com/Peralta-CashFlow/CashFlow-UI);

### Utilities

- [CashFlow-Workflows](https://github.com/Peralta-CashFlow/CashFlow-WorkFlows);
- [CashFlow-Libraries](https://github.com/Peralta-CashFlow/CashFlow-Libraries);

### Docker

- [CashFlow-Compose](https://github.com/Peralta-CashFlow/CashFlow-Compose);

# Project Organization

For the project organization we will use [GitHub Projects](https://github.com/Peralta-CashFlow/.github/projects) to create a kind of Scrum board where we will define the US to be developed and also the tasks
that must be linked to PRs making it easier to track the development evolution.

## Documentation

All applications will have a GitHub pages with Swagger documentation to help on understanding.

## Good Practices

We strongly believe that good practices are the pillar to develop an amazing solution. Here are some of ours practices:

- Unit Tests: All APIs need to have at least 80% of code coverage;
- Clean Code: Will use [SonarQube](https://www.sonarsource.com/) to maintain our code clean;
- Commits: All commits should follow [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) standards;

* All those practices will be enforced with the help of [GitHub Actions](https://github.com/features/actions).

## Technologies

- [JavaScript - React](https://react.dev/);
- [Java - SpringBoot](https://spring.io/projects/spring-boot);
- [Docker](https://www.docker.com/);
- [MySQL](https://www.mysql.com/);
- [Jenkins](https://www.jenkins.io/);
- [SonarQube](https://www.sonarsource.com/products/sonarqube);
- [GitHub Actions](https://github.com/features/actions);

# Containerization

The project is containerized using Docker, which allows for easy deployment and scaling. 
The Docker Compose file orchestrates the different services, making it simple to run the entire application stack locally or in production.

You can find the Docker Compose file and the documentation to run it in the [CashFlow-Compose](https://github.com/Peralta-CashFlow/CashFlow-Compose) repository.

## Team

- [Vinicius Peralta](https://www.linkedin.com/in/vinicius-peralta/);

## Reach Out

Feel free to reach out if you have any doubts or suggestions! 

<a href="mailto:vinicius-peralta@hotmail.com" target="_blank">
  <img src="https://github.com/user-attachments/assets/78131001-6300-4d17-bad6-4c9dbd2e4ca5" alt="Email" title="Email" width="32" height="32">
</a>
