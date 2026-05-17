# QA API Automation Framework

API automation framework designed for validating REST APIs using Postman, Newman, and GitHub Actions CI/CD.

---

## Project Overview

This framework validates REST API endpoints with automated API tests, response validations, and reporting support.

The project demonstrates:

* API automation testing
* CRUD API validation
* Response assertions
* Environment configuration
* Newman execution
* HTML reporting
* GitHub Actions CI/CD integration

---

## Tech Stack

* Postman
* Newman
* Node.js
* GitHub Actions
* JavaScript

---

## Project Structure

```plaintext
qa-api-automation-framework
│
├── collections
│   └── reqres_collection.json
│
├── environments
│   └── qa_environment.json
│
├── reports
│   └── report.html
│
├── test-data
│   └── users.json
│
├── .github
│   └── workflows
│       └── api-tests.yml
│
├── package.json
├── .gitignore
└── README.md
```

---

## Features

* REST API Testing
* CRUD Operations Validation
* Response Time Validation
* Status Code Assertions
* Environment-based execution
* HTML Test Reports
* CI/CD Automation with GitHub Actions

---

## Running Tests Locally

Install dependencies:

```bash
npm install --legacy-peer-deps
```

Run tests:

```bash
npm run test
```

---

## GitHub Actions CI/CD

This project uses GitHub Actions to automatically execute API tests on every push to the main branch.

Workflow includes:

* Repository checkout
* Node.js setup
* Dependency installation
* Newman test execution

---

## Test Report

HTML reports are generated automatically after execution inside:

```plaintext
reports/report.html
```

---

## Sample API Tested

Public API used for automation practice:

```plaintext
https://reqres.in
```

---

## Author

Neha Chawla
Senior QA Automation Engineer

Skills:

* Playwright
* Selenium
* API Testing
* Postman
* Performance Testing
* GitHub Actions
* CI/CD
* Agile QA
