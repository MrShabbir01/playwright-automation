# Automation Testing Portfolio — Ostad Project

This repository contains two separate testing projects developed as part of my QA learning journey: UI test automation using Playwright and API testing using Postman and Newman.

## Repository Contents

| Project | Tools |
|---|---|
| Playwright UI Automation | Playwright, Node.js, npm |
| ReqRes API Testing | Postman, Newman, ReqRes API |

---

# 1. Playwright UI Automation

Overview

This project contains browser-based UI automation tests using Playwright. It supports sequential and parallel test execution.

## Prerequisites

Install the following before running the project:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)

## Setup

**1. Clone the repository**

```bash
git clone https://github.com/MrShabbir01/playwright-automation.git
```

**2. Navigate to the project directory**

```bash
cd playwright-automation
```

**3. Install dependencies**

```bash
npm install
```

**4. Install Playwright browsers**

```bash
npx playwright install
```

## Test Execution

The project supports sequential and parallel test execution.

### Sequential Execution

Run tests one after another:

```bash
npm run test:sequential
```

### Parallel Execution

Run tests using parallel execution:

```bash
npm run test:parallel
```

Parallel execution behavior depends on the Playwright configuration and the project's test scripts.

## Test Reports

After test execution, check the terminal output for the test results.

### HTML Report

If the project is configured to use Playwright's HTML reporter, generate or open the report with:

```bash
npx playwright show-report
```

# 2. ReqRes API Testing — Postman and Newman

## Overview

This project uses a Postman collection to test the ReqRes API. Newman is used to execute the collection from the command line.

### Prerequisites

- Node.js and npm
- An exported Postman collection in JSON format

### Setup

**Step 1: Extract the project**

Extract `Ostad_ReqRes_API.zip` into a separate directory.

**Step 2: Install Newman**

```bash
npm install -g newman
```

**Step 3: Verify the installation**

```bash
newman --version
```

### Test Execution

**Run the Postman collection**

Open a terminal in the directory containing the exported collection and execute:

```bash
newman run ReqRes demo.postman_collection2.json
```

---
