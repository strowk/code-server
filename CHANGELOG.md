<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
# Changelog

- [Changelog](#changelog)
  - [3.11.0](#3110)
    - [New Features](#new-features)
    - [Bug Fixes](#bug-fixes)
    - [Documentation](#documentation)
    - [Development](#development)
  - [3.10.0](#3100)
    - [New Features](#new-features-1)
    - [Bug Fixes](#bug-fixes-1)
    - [Documentation](#documentation-1)
    - [Development](#development-1)
  - [Previous versions](#previous-versions)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Changelog

<!--

This should be updated on every PR.

We copy from here into the release notes.

 -->

<!--
Add next version above previous version but below this line using the template

## 0.0.0

VS Code v0.00.0

### New Features

- item

### Bug Fixes

- fix(socket): did this thing #321 @githubuser

### Documentation

- item

### Development

- item

-->

## 3.11.0

VS Code v1.56

### New Features

- item

### Bug Fixes

- fix: Check the logged user instead of $USER #3330 @videlanicolas
- fix: Fix broken node_modules.asar symlink in npm package #3355 @code-asher

### Documentation

- docs(install): add raspberry pi section #3376 @jsjoeio
- docs(maintaining): add pull requests section #3378 @jsjoeio
- docs(maintaining): add merge strategies section #3379 @jsjoeio
- docs(maintaining): add process for release managers #3360 @jsjoeio

### Development

- chore: ignore updates to microsoft/playwright-github-action
- fix(socket): use xdgBasedir.runtime instead of tmp #3304 @jsjoeio

## 3.10.0

VS Code v1.56

### New Features

- feat: minor connections refactor #3178 @code-asher
- feat(security): add code-scanning with CodeQL #3229 @jsjoeio
- feat(ci): add trivy job for security #3261 @jsjoeio
- feat(vscode): update to version 1.56.0 #3269 @oxy
- feat: use ptyHostService #3308 @code-asher

### Bug Fixes

- fix(socket): did this thing #321 @githubuser
- fix(login): rate limiter shouldn't count successful logins #3141 @jsjoeio
- chore(lib/vscode): update netmask #3187 @oxy
- chore(deps): update dependencies with CVEs #3223 @oxy
- fix: refactor logout #3277 @code-asher
- fix: add flag for toggling permessage-deflate #3286 @code-asher
- fix: make sure directories exist #3309 @code-asher

### Documentation

- docs(FAQ): add mention of sysbox #3087 @bpmct
- docs: add security policy #3148 @jsjoeio
- docs(guide.md): add `caddy` example for serving from sub-path #3217 @catthehacker
- docs: revamp debugging section #3224 @code-asher
- docs(readme): refactor to use codecov shield #3227 @jsjoeio
- docs(maintaining): use milestones over boards #3228 @jsjoeio
- docs(faq): add entry for accessing OSX folders #3247 @bpmct
- docs(termux): add workaround for Android backspace issue #3251 @jsjoeio
- docs(maintaining): add triage to workflow #3284 @jsjoeio
- docs(security): add section for tools #3287 @jsjoeio
- docs(maintaining): add versioning #3288 @jsjoeio
- docs: add changelog #3337 @jsjoeio

### Development

- fix(update-vscode): add check/docs for git-subtree #3129 @oxy
- refactor(testing): migrate to playwright-test from jest-playwright #3133 @jsjoeio
- refactor(ci): remove unmaintained CI images and update release workflow #3147 @oxy
- chore(ci): migrate from hub to gh #3168 @oxy
- feat(testing): add e2e tests for code-server and terminal #3169 @jsjoeio
- chore(ranger): fix syntax for extension-request #3172 @oxy
- feat(testing): add codecov to generate test coverage reports #3194 @jsjoeio
- feat(testing): add tests for registerServiceWorker #3200 @jsjoeio
- refactor(testing): fix flaky terminal test #3230 @jsjoeio
- chore: ignore 15.x @types/node updates #3244 @jsjoeio
- chore(build): compile vscode+extensions in parallel #3250 @oxy
- fix(deps): remove eslint-plugin-jest-playwright #3260 @jsjoeio
- fix(testing): reduce flakiness of terminal.test.ts and use 1 worker for e2e tests #3263 @jsjoeio
- feat(testing): add isConnected check #3271 @jsjoeio
- feat(testing): add test for src/node/constants.ts #3290 @jsjoeio
- feat: test static route #3297 @code-asher
- refactor(ci): split audit from prebuild #3298 @oxy
- chore(lib/vscode): cleanup/update build deps #3314 @oxy
- fix(build): download correct cloud-agent for arch #3331 @oxy
- fix: xmldom and underscore #3332 @oxy

## Previous versions

This was added with `3.10.0`, which means any previous versions are not documented in the changelog.

To see those, please visit the [Releases page](https://github.com/cdr/code-server/releases).
