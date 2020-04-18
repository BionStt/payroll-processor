# Payroll Processor

Sample HRIS application where a list of employees and their payroll information would be available in report format.

## Build status

### Api

![dotnet core payroll-processor-api - build](https://github.com/KyleMcMaster/payroll-processor/workflows/dotnet%20core%20payroll-processor-api%20-%20build/badge.svg)

### Client

![.github/workflows/npm.yml](https://github.com/KyleMcMaster/payroll-processor/workflows/.github/workflows/npm.yml/badge.svg) [![Styled with Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io)

### Functions

![dotnet core payroll-processor-functions - build](https://github.com/KyleMcMaster/payroll-processor/workflows/dotnet%20core%20payroll-processor-functions%20-%20build/badge.svg?branch=master)

## Motivation

This project was created to explore a variety of technologies and patterns I use daily in one place to get a better understanding of those technologies.

Things I would like to explore:

- Functional Programming
- Automated Tests
- Basics of Angular, TypeScript, Rxjs, and Bootstrap
- Synergy that exists between Azure Functions and .Net Core Web Apis
  - Implementations of comparable endpoints in both projects to evaluate the tooling and ecosystems
- Having fun!

## Roadmap

- MVP

  - Initial Employee CRUD functionality
  - Initial Payroll CRUD functionality
  - Basic charting and analytics of payroll data

- TODOs

  - Move seed data to CosmosDB document instead of boilerplate c# code
  - Refactor client to use Akita state management
  - Toggle between Api and Azure Function backends
  - Advanced analytics like payroll totals by department, risk, and time

## Feedback and Contributing

Feel free to open PRs with additional examples, tests, or refactorings.

## References
