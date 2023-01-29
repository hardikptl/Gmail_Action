
# Java Selenium Project with Maven (Action-CI)

This Project Automate Gmail login process. Test data coming from data provider that read data from excel file and feeds to test methods.
Created github action for maven build and Test for continous integration.

## continuous integration

![Build](https://github.com/hardikptl/Gmail_Action/blob/main/.github/workflows/main.yml/badge.svg)
[![Language: Java](https://img.shields.io/badge/Language-Java-orange.svg)](https://github.com/hardikptl/Gmail_Action)

## Features

- Object-oriented design with Page Object Model (POM)
- Reading data from Excel
- Built-in reporting and logging
- Used Data Provider Annotation
- Support for parallel test execution

## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies/ update project

```bash
  mvn clean install -U
```

Build Project

```bash
  mvn build
```
Or Run Test
```bash
  mvn test
```
