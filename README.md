# java-cli-maven-surefire-pmd-jacoco-junit-test-car-data

## Description
A POC for sprimg app using JUnit
framework with jacoco, pmd and surefire
plugins.

## Tech stack
- java
- maven
  - spring
  - junit
  - surefire
  - jacoco
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://github.com/eugenp/tutorials/tree/master/maven-modules/maven-integration-test)
- [Jacoco config](https://www.baeldung.com/jacoco)
