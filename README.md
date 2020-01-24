# Automated CHANGELOG

This is a test branch to try out `standard-version`

### References

- https://github.com/conventional-changelog/standard-version
- https://www.conventionalcommits.org/en/v1.0.0/
- https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines
- https://medium.com/@menuka/writing-meaningful-git-commit-messages-a62756b65c81

## Install

```sh
$ npm install standard-version --save-dev
```

Add a script

```json
"scripts": {
    "release": "standard-version"
  }
```

Run the Script

```sh
$ npm run release
```

## Quick rundown

Message that will be used for Features and Bug Fixes

> feat: this is a feature added

> fix: this is a bug fix

Add an exclamation(!) to indicate breaking changes

> feat!: this is a breaking change feature

Use `refactor:` when making small commits

## Types of commit messages:

- build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- ci: Changes to CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
- docs: Documentation only changes
- feat: A new feature
- fix: A bug fix
- perf: A code change that improves performance
- refactor: A code change that neither fixes a bug nor adds a feature
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- test: Adding missing tests or correcting existing tests