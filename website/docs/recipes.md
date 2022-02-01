---
id: recipes
title: Overview
description: Recipes and pre-built integrations to test common scenarios in Pact
---

Recipes and pre-built integrations to test common scenarios in Pact

| Recipe/Integratino                                 | Description                                                                                                                         |
| -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| [GraphQL](recipes/graphql)                         | Strategies for testing GraphQL endpoints (example with Apollo)                                                                      |
| [API Gateway](recipes/apigateway)                  | Strategies for dealing with API Gateways, such as AWS API Gateway, Kong etc.                                                        |
| [Lambda/FaaS (Asynchronous)](recipes/lambdaasync)  | How to write contract tests for asynchronous lambda functions / FaaS                                                                |
| [Lambda (HTTP)](recipes/lambdahttp)                | How to write contract tests for HTTP based lambdas with AWS SAM                                                                     |
| [Cypress](recipes/cypress)                         | Best practices for integrating Pact with Cypress, and converting your cypress `cy.route()` / `cy.intercept()` calls into pact files |
| [MSW](https://github.com/you54f/msw-pact)          | Library for integrating MSW with Pact                                                                                               |
| [NestJS](https://github.com/omermorad/nestjs-pact) | Library for integrating Pact with NestJS                                                                                            |
| [Kafka](recipes/kafka)                             | How to test Kafka messages with Pact                                                                                                |