# Jenkins and Continuous Testing Lab

## Project Overview
This project demonstrates Continuous Integration using Jenkins with
Freestyle and Multibranch Pipeline jobs.

## Technologies
- Java
- Maven
- Jenkins
- GitHub

## Branch Strategy
- main: Full CI pipeline
- feature/*: Test-only pipeline
- release/*: Testing and validation

## How to Run
1. Clone repository
2. Run mvn clean test
3. Configure Jenkins jobs


| Assignment Requirement | File                |
| ---------------------- | ------------------- |
| Java code              | Calculator.java     |
| Unit tests             | CalculatorTest.java |
| Build tool             | pom.xml             |
| Multibranch logic      | Jenkinsfile         |
| Freestyle batch step   | build.sh            |
| Docker                 | Dockerfile          |
| Documentation          | README.md           |
