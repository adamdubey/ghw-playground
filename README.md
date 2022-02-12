# Github Workflows & Actions Playground

A basic Github CI/CD workflow for supporting Front-End Web Applications & Projects.

## Workflow Overview

1. Create a new `feature branch` from `dev`
2. Make changes, Run Unit tests, Iterate
3. Submit a PR
4. CI Workflow runs, if checks and tests pass, merge into `dev` and deploy to `STAGING` environment
5. A new Pull Request from `dev` into `main` is created
6. CI Workflow runs, if checks and tests pass, merge into `main` and deploy to `PRODUCTION` environment

---

## Quick Start

_For running the React.js application locally:_

```sh
# Install dependencies
npm install

# Start the app
npm run start

# in browser, visit http://localhost:3000
# to STOP, Ctrl+C in Terminal
```

---

## Technologies & Frameworks

- [Codecov](https://app.codecov.io/)
- [CommitLint](https://github.com/conventional-changelog/commitlint)
- [Commitizen](https://github.com/commitizen/cz-cli)
- [Create React App](https://reactjs.org/docs/create-a-new-react-app.html)
- [Husky](https://typicode.github.io/husky/#/)
- [Github Workflows](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [Prettier](https://prettier.io/)
- [React](https://reactjs.org/)
- [Semantic Release](https://github.com/semantic-release/semantic-release)
- [Slack](https://slack.com/)
- [Surge](https://surge.sh/)

---

### Endpoints

![](https://github.com/adamdubey/ghw-playground/workflows/CI/badge.svg?branch=dev&event=push)

- [Staging](http://loose-airplane.surge.sh)
- [Production](http://fresh-fact.surge.sh)
