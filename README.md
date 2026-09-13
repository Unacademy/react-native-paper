# react-native-paper

> Material Design for React Native (Android & iOS)

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**react-native-paper** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

Material Design for React Native (Android & iOS)

**Topics / Tags:** `approvers-1`

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | React Native |
| **Package Manager** | — |

### Dependencies

**Runtime Dependencies:**
- `@callstack/react-theme-provider`
- `color`
- `react-native-safe-area-view`

**Dev Dependencies:**
- `@babel/core`
- `@babel/runtime`
- `@callstack/eslint-config`
- `@commitlint/config-conventional`
- `@react-native-community/bob`
- `@release-it/conventional-changelog`
- `@types/color`
- `@types/jest`
- `@types/node`
- `@types/react-dom`


---

## Repository Structure

```
react-native-paper/
├── .all-contributorsrc
├── .circleci/
│   ├── comment-artifacts.sh
│   ├── config.yml
│   ├── deploy-docs.sh
├── .editorconfig
├── .eslintignore
├── .eslintrc
├── .flowconfig
├── .github/
│   ├── ISSUE_TEMPLATE
│   ├── PULL_REQUEST.md
│   ├── workflows
├── .gitignore
├── .prettierrc
├── .release-it.json
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE.md
├── README.md
├── babel.config.js
├── babel.js
├── commitlint.config.js
├── docs/
│   ├── .babelrc
│   ├── .gitignore
│   ├── assets
│   ├── component-docs.config.js
│   ├── components
├── example/
│   ├── .eslintrc
│   ├── .expo-shared
│   ├── .gitignore
│   ├── App.js
│   ├── App.web.js
... (truncated)
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|


> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
# 1. Clone the repository
git clone git@github.com:unacademy/react-native-paper.git
cd react-native-paper

# 2. Install dependencies
npm install      # or yarn install
```

### Available Scripts

```bash
# typescript
npm run typescript   # tsc --noEmit

# lint
npm run lint   # eslint --ext '.js,.ts,.tsx' .

# test
npm run test   # jest

# prepare
npm run prepare   # bob build && node ./scripts/generate-mappings.js

# release
npm run release   # release-it

# bootstrap
npm run bootstrap   # yarn --cwd example && yarn --cwd docs && yarn

# docs
npm run docs   # yarn --cwd docs

# example
npm run example   # yarn --cwd example

```


---

## Running the Application

_Refer to the project's build system or CI configuration._

---

## Infrastructure & CI/CD

- CI/CD pipeline configured (`.github/workflows` or equivalent)
- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> <p align="center">
  <img alt="react-native-paper" src="docs/assets/images/paper-logo.svg?sanitize=true" width="300">
</p>
<p align="center">
  Material design for React Native.<br/>
  <a href="https://reactnativepaper.com">reactnativepaper.com</a>
</p>

---

[![Greenkeeper badge](https://badges.greenkeeper.io/callstack/react-native-paper.svg)](https://greenkeeper.io/)

[![Build Status][build-badge]][build]
[![Version][version-badge]][package]
[![MIT License][license-badge]][license]
[![All Contributors][all-contributors-badge]][all-contributors]
[![PRs Welcome][prs-welcome-badge]][prs-welcome

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
