# Playwright POM Starter

Page Object Model scaffold for **Playwright** — a clean base used for framework rollouts and CoE training.

![Playwright](./playwright-logo.png)

## Overview

Simple automation test framework written with **TypeScript / JavaScript** and Playwright, implementing the Page Object Model pattern. Suitable as a starter for enterprise framework customisation.

## Features

- Page Object Model under `pages/` and `framework/`
- E2E suites and examples (`e2e/`, `tests/`, `tests-examples/`)
- Dual config support (`playwright.config.ts` / `.js`)
- GitHub Actions–ready layout (`.github/`)

## Stack

- Playwright
- TypeScript / JavaScript
- Node.js

## Getting started

```bash
npm install
npx playwright install

npx playwright test
npx playwright test --headed
npx playwright test --ui
```

## Project layout

```
pages/                 page objects
framework/             shared framework helpers
PlaywrightFrameWork/   extended framework modules
e2e/ · tests/          executable suites
tests-examples/        sample specs
```

## Author

**Pushanshu Avinash Sharma** — QA Automation Architect / Lead SDET  
[GitHub](https://github.com/Avinash258) · [LinkedIn](https://www.linkedin.com/in/p-avinash-sharma-8b0203b9/) · [Portfolio](https://avinash258.github.io/Protfolio/)
