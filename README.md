# Playwright Automation — Ostad Project

A personal test automation project using Playwright to practice browser-based testing and automated test execution.

## Tech Stack

- Playwright
- Node.js
- npm

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
