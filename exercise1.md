# Exercise 1

In the hypothetical situation, there is 6 people working on same application. The application is coded with Java. 

## Linting
For linting, there is a development tool called [checkstyle](https://checkstyle.org/)

## Testing
For testing, there is few options, depending on test type.

- JUnit for unit tests
- TestNG, another option for unit tests
- Selenium for UI tests

## Building
For building the project, there is an option to use [Maven](https://docs.github.com/en/actions/guides/building-and-testing-java-with-maven) which can be used to build and test the project. Maven is a build automation tool that handles the dependencies required by the project.

## Alternatives for Jenkins and GitHub Actions
- CircleCI
- GitLab CI
- TeamCity
- Bamboo
- Buddy
- Travis CI

## Self-hosted vs Cloud-based environment

Using self-hosted vs cloud-based option for CI depends on following factors:
- Is there an requirement for complex setups in CI? If **yes**, then self-hosted environment is the best option
- Are there a lot of resource-intesive operations being done in CI? If **yes**, then self-hosted might be the best option. Cloud-based options are billed by build time so it might be costly to use them if, for example, builds are slow.
- How many developers the company have in overall (assuming they work in a company)? If there is a lot of developers, the self-hosted is probably the best option for reducing costs and better support for customizability.